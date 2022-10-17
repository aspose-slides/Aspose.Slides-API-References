---
title: DocumentProperties
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/documentproperties/
---

## DocumentProperties class

 Represents properties of a presentation.
 

## Constructors

| Name | Description |
| --- | --- |
| [DocumentProperties](documentproperties)() | Initializes new instance of class DocumentProperties. |

## Methods

| Name | Description |
| --- | --- |
| [clearBuiltInProperties](clearbuiltinproperties)() | Clears and sets default values for all builtIn properties. |
| [clearCustomProperties](clearcustomproperties)() | Removes all custom properties. |
| [cloneT](clonet)() | Clones current object |
| [containsCustomProperty](containscustomproperty)(String) | Check presents of a custom property with a specified name. |
| [deepClone](deepclone)() | Clones current object |
| [getAppVersion](getappversion)() | Returns the app version. Read-only String. |
| [getApplicationTemplate](getapplicationtemplate)() | Returns or sets the template of a application. Read/write String. |
| [getAuthor](getauthor)() | Returns or sets the author of a presentation. Read/write String. |
| [getCategory](getcategory)() | Returns or sets the category of a presentation. Read/write String. |
| [getComments](getcomments)() | Returns or sets the comments of a presentation. Read/write String. |
| [getCompany](getcompany)() | Returns or sets the company property. Read/write String. |
| [getContentStatus](getcontentstatus)() | Returns or sets the content status of a presentation. Read/write String. |
| [getContentType](getcontenttype)() | Returns or sets the content type of a presentation. Read/write String. |
| [getCountOfCustomProperties](getcountofcustomproperties)() | Returns the number of custom properties actually contained in a collection. Read-only int. |
| [getCreatedTime](getcreatedtime)() | Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date. |
| [getCustomPropertyName](getcustompropertyname)(int) | Return a custom property name at the specified index. |
| [getCustomPropertyValue](getcustompropertyvalue)(String, boolean[]) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue](getcustompropertyvalue)(String, int[]) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue](getcustompropertyvalue)(String, java.util.Date[]) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue](getcustompropertyvalue)(String, java.lang.String[]) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue](getcustompropertyvalue)(String, float[]) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue](getcustompropertyvalue)(String, double[]) | Gets a named double value from the custom properties. |
| [getHyperlinkBase](gethyperlinkbase)() | Returns or sets the HyperlinkBase document property. Read/write String. |
| [getKeywords](getkeywords)() | Returns or sets the keywords of a presentation. Read/write String. |
| [getLastPrinted](getlastprinted)() | Returns the date when a presentation was printed last time. Read/write java.util.Date. |
| [getLastSavedBy](getlastsavedby)() | Returns or sets the name of a last person who modified a presentation. Read/write String. |
| [getLastSavedTime](getlastsavedtime)() | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) method summary. |
| [getManager](getmanager)() | Returns or sets the manager property. Read/write String. |
| [getNameOfApplication](getnameofapplication)() | Returns or sets the name of the application. Read/write String. |
| [getPresentationFormat](getpresentationformat)() | Returns or sets the intended format of a presentation. Read/write String. |
| [getRevisionNumber](getrevisionnumber)() | Returns or sets the presentation revision number. Read/write int. |
| [getSharedDoc](getshareddoc)() | Determines whether the presentation is shared between multiple people. Read/write boolean. |
| [getSubject](getsubject)() | Returns or sets the subject of a presentation. Read/write String. |
| [getTitle](gettitle)() | Returns or sets the title of a presentation. Read/write String. |
| [getTotalEditingTime](gettotaleditingtime)() | Total editing time of a presentation. Read/write double. |
| [get_Item](get_item)(String) | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |
| [removeCustomProperty](removecustomproperty)(String) | Remove a custom property associated with a specified name. |
| [setApplicationTemplate](setapplicationtemplate)(String) | Returns or sets the template of a application. Read/write String. |
| [setAuthor](setauthor)(String) | Returns or sets the author of a presentation. Read/write String. |
| [setCategory](setcategory)(String) | Returns or sets the category of a presentation. Read/write String. |
| [setComments](setcomments)(String) | Returns or sets the comments of a presentation. Read/write String. |
| [setCompany](setcompany)(String) | Returns or sets the company property. Read/write String. |
| [setContentStatus](setcontentstatus)(String) | Returns or sets the content status of a presentation. Read/write String. |
| [setContentType](setcontenttype)(String) | Returns or sets the content type of a presentation. Read/write String. |
| [setCreatedTime](setcreatedtime)(Date) | Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date. |
| [setCustomPropertyValue](setcustompropertyvalue)(String, boolean) | Sets a named boolean custom property. |
| [setCustomPropertyValue](setcustompropertyvalue)(String, int) | Sets a named integer custom property. |
| [setCustomPropertyValue](setcustompropertyvalue)(String, Date) | Sets a named DateTime custom property. |
| [setCustomPropertyValue](setcustompropertyvalue)(String, String) | Sets a named string custom property. |
| [setCustomPropertyValue](setcustompropertyvalue)(String, float) | Sets a named float custom property. |
| [setCustomPropertyValue](setcustompropertyvalue)(String, double) | Sets a named double custom property. |
| [setHyperlinkBase](sethyperlinkbase)(String) | Returns or sets the HyperlinkBase document property. Read/write String. |
| [setKeywords](setkeywords)(String) | Returns or sets the keywords of a presentation. Read/write String. |
| [setLastPrinted](setlastprinted)(Date) | Returns the date when a presentation was printed last time. Read/write java.util.Date. |
| [setLastSavedBy](setlastsavedby)(String) | Returns or sets the name of a last person who modified a presentation. Read/write String. |
| [setLastSavedTime](setlastsavedtime)(Date) | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) method summary. |
| [setManager](setmanager)(String) | Returns or sets the manager property. Read/write String. |
| [setNameOfApplication](setnameofapplication)(String) | Returns or sets the name of the application. Read/write String. |
| [setPresentationFormat](setpresentationformat)(String) | Returns or sets the intended format of a presentation. Read/write String. |
| [setRevisionNumber](setrevisionnumber)(int) | Returns or sets the presentation revision number. Read/write int. |
| [setSharedDoc](setshareddoc)(boolean) | Determines whether the presentation is shared between multiple people. Read/write boolean. |
| [setSubject](setsubject)(String) | Returns or sets the subject of a presentation. Read/write String. |
| [setTitle](settitle)(String) | Returns or sets the title of a presentation. Read/write String. |
| [setTotalEditingTime](settotaleditingtime)(double) | Total editing time of a presentation. Read/write double. |
| [set_Item](set_item)(String, Object) | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |
