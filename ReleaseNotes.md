## 0.13.0/1/2/3
Security enhancements:
- improved session and cookie security 
- CSRF token
- click hijacking warning
- gui.loginTimeout configuration

## 0.12.12
- table: filter improvements (select options)
- table: paginator reset after search or page out of result
- table: div with optimal heigth and width

## 0.12.11
- table: filter improvements (date picker, default values, ...)

## 0.12.10
- fix and make `col/row.addView( {id:"xy", ...}, ... )` 
  working in [complex layouts](https://github.com/ma-ha/easy-web-app/blob/master/examples/complex-layout/index.js) (instead of using `rowId` or `columnId`)

## 0.12.9
- [IO graph](https://github.com/ma-ha/easy-web-app/tree/master/examples/io) zoom x-axis (ReST-Web-UI 0.9.17)

## 0.12.8
- redirect unautenticated users to "main" or `needLoginPage`

## 0.12.6/7
- IO improvements: Button with visual feedback / pollOptions settings /fixes

## 0.12.4/5
- Table: enhanced date format 

## 0.12.2
- IO graph y-axis scaling supports multi-touch

## 0.12.1
- support ReST-Web-UI 0.9.7, with scalable IO graphs
 
## 0.12
- important security fix: header elements (pull down) hidden in non authorized redirects

## 0.11.7/8
- Support ReST-Web-UI 0.9.6, with I/O graph x-axis grid 
- added graph to [IO demo](https://github.com/ma-ha/easy-web-app/tree/master/examples/io) 

## 0.11.6
- Support ReST-Web-UI 0.9.5, with I/O graph time lines

## 0.11.5 
- I/O addIoElementConfig with callback param (e.g.button)

## 0.11.4 
- fix for I/O when using a root-path

## 0.11.3
- Support ReST-Web-UI 0.9.2, with I/O update hook and improved info URL parameter "?info=m1,m2"

## 0.11.1/2
* Support ReST-Web-UI 0.9.2, with date columns in tabe (editable, with datepicker)

## 0.11.0
* Solved path issues using newer npm versions (result in 404 and empty page)

## 0.10.2/3
* ioView.addIoElementConfig(...) see [IO-API](https://github.com/ma-ha/easy-web-app/tree/master/examples/io) 
* fix in I/O switch

## 0.10.0
* [new API functions](https://github.com/ma-ha/easy-web-app/blob/master/API-Reference.md#page-api-reference) 
in mainPage to customize the footer: 
[example](https://github.com/ma-ha/easy-web-app/blob/master/examples/footer/index.js)

## 0.9.18
* upgrade to ReST-Web-UI 0.9.0

## 0.9.17
* fix table bug by ReST-Web-UI 0.8.9

## 0.9.16
* Icon navigation view with [example](https://github.com/ma-ha/easy-web-app/tree/master/examples/icons) 

## 0.9.14
* List with polling updates

## 0.9.13
* List/table can display graph, incl. [example](https://github.com/ma-ha/easy-web-app/tree/master/examples/list) 

## 0.9.11
* List/table with pie chart, incl. [example](https://github.com/ma-ha/easy-web-app/tree/master/examples/list) 

## 0.9.11
* List/table improvements from Rest-Web-UI 0.8.3
* List [example](https://github.com/ma-ha/easy-web-app/tree/master/examples/list)

## 0.9.10
* Lists with hierarchically DIVs

## 0.9.9
* Request password change from server side and open dialog after login
* new Rest-Web-UI Features:
	* Search in header
	* RSS

## 0.9.8
* Change password: strength check

## 0.9.6
* ReST API authentication and [example](https://github.com/ma-ha/easy-web-app/tree/master/examples/security)

## 0.9.5
Support rest-web-gui v0.7.20:
* security: change password
* security: user pages
* security: pull down menu

## 0.9.1, 0.9.2
* Security module support password changes
* Not authorized page redirect to login page
* security hooks with callback enable asynchronous operation

## 0.9.0
* `init()` supports location parameter to run portal not only on `/`

## 0.8.0
* Pull-down menu [API](https://github.com/ma-ha/easy-web-app/tree/master/examples#guiaddpulldownmenu--menuid-menulabel-), 
  see also [example](https://github.com/ma-ha/easy-web-app/blob/master/examples/pull-down-menu/index.js)

### 0.8.1
* Authorization checks also for pull-down modules implemented.
  
### 0.8.2
* Tree support: dependency to [rest-web-ui](https://github.com/ma-ha/rest-web-ui/tree/master/html/modules/pong-tree)

### 0.8.2
* API helper:
	* [page.setPageWidth](https://github.com/ma-ha/easy-web-app/tree/master/examples#pagesetpagewidth--width-)
	
### 0.8.5
* support rest-web-gui@0.7.15 
	* table auto load changed
	* histogram view is available
	* fixes

### 0.8.6
* support tree and histogram (demos available) 
** requires rest-web-gui@0.7.16 


## v0.7.0
* Support [security plugin](https://github.com/ma-ha/rest-web-ui/tree/master/html/modules/pong-security),
  see [API ref](https://github.com/ma-ha/easy-web-app/tree/master/examples#guienablesecurity-paramsobj-) 
  and [example](https://github.com/ma-ha/easy-web-app/blob/master/examples/security/index.js)

## v0.6.2
* [custom CSS example](https://github.com/ma-ha/easy-web-app/tree/master/examples/custom-css) extended 

## v0.6
* [API](https://github.com/ma-ha/easy-web-app/tree/master/examples#guiaddlang--languageid--translations-) for i18n: [i18n example](https://github.com/ma-ha/easy-web-app/blob/master/examples/i18n/index.js)

## v0.5
* mobile phone, tablet or desktop browser detection: [mobile layout example](https://github.com/ma-ha/easy-web-app/tree/master/examples/mobile-detect) 

## v0.4
* [added examples](https://github.com/ma-ha/easy-web-app/tree/master/examples)
* [added form tutorial](https://github.com/ma-ha/easy-web-app/tree/master/examples/form-tutorial)
* [API reference docu](https://github.com/ma-ha/easy-web-app/tree/master/examples#api-reference)