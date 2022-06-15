---
title: DocumentProperties
type: docs
weight: 0
url: /php-java/documentproperties/
---

# DocumentProperties class

 Represents properties of a presentation.
 

## Constructors

| name | description |
| --- | --- |
| [DocumentProperties](/slides/php-java/documentproperties/documentproperties/)() | Initializes new instance of class DocumentProperties. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [clearBuiltInProperties](/slides/php-java/documentproperties/clearbuiltinproperties/)() | void | Clears and sets default values for all builtIn properties. |
| [clearCustomProperties](/slides/php-java/documentproperties/clearcustomproperties/)() | void | Removes all custom properties. |
| [cloneT](/slides/php-java/documentproperties/clonet/)() | IDocumentProperties | Clones current object |
| [containsCustomProperty](/slides/php-java/documentproperties/containscustomproperty/)(String) | boolean | Check presents of a custom property with a specified name. |
| [deepClone](/slides/php-java/documentproperties/deepclone/)() | Object | Clones current object |
| [getAppVersion](/slides/php-java/documentproperties/getappversion/)() | String | Returns the app version. Read-only String. |
| [getApplicationTemplate](/slides/php-java/documentproperties/getapplicationtemplate/)() | String | Returns or sets the template of a application. Read/write String. |
| [getAuthor](/slides/php-java/documentproperties/getauthor/)() | String | Returns or sets the author of a presentation. Read/write String. |
| [getCategory](/slides/php-java/documentproperties/getcategory/)() | String | Returns or sets the category of a presentation. Read/write String. |
| [getComments](/slides/php-java/documentproperties/getcomments/)() | String | Returns or sets the comments of a presentation. Read/write String. |
| [getCompany](/slides/php-java/documentproperties/getcompany/)() | String | Returns or sets the company property. Read/write String. |
| [getContentStatus](/slides/php-java/documentproperties/getcontentstatus/)() | String | Returns or sets the content status of a presentation. Read/write String. |
| [getContentType](/slides/php-java/documentproperties/getcontenttype/)() | String | Returns or sets the content type of a presentation. Read/write String. |
| [getCountOfCustomProperties](/slides/php-java/documentproperties/getcountofcustomproperties/)() | int | Returns the number of custom properties actually contained in a collection. Read-only int. |
| [getCreatedTime](/slides/php-java/documentproperties/getcreatedtime/)() | Date | Returns the date when a presentation was created. Read/write java.util.Date. |
| [getCustomPropertyName](/slides/php-java/documentproperties/getcustompropertyname/)(int) | String | Return a custom property name at the specified index. |
| [getCustomPropertyValue](/slides/php-java/documentproperties/getcustompropertyvalue/)(String, boolean[]) | void | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue](/slides/php-java/documentproperties/getcustompropertyvalue/)(String, int[]) | void | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue](/slides/php-java/documentproperties/getcustompropertyvalue/)(String, java.util.Date[]) | void | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue](/slides/php-java/documentproperties/getcustompropertyvalue/)(String, java.lang.String[]) | void | Gets a named string value from the custom properties. |
| [getCustomPropertyValue](/slides/php-java/documentproperties/getcustompropertyvalue/)(String, float[]) | void | Gets a named float value from the custom properties. |
| [getCustomPropertyValue](/slides/php-java/documentproperties/getcustompropertyvalue/)(String, double[]) | void | Gets a named double value from the custom properties. |
| [getHyperlinkBase](/slides/php-java/documentproperties/gethyperlinkbase/)() | String | Returns or sets the HyperlinkBase document property. Read/write String. |
| [getKeywords](/slides/php-java/documentproperties/getkeywords/)() | String | Returns or sets the keywords of a presentation. Read/write String. |
| [getLastPrinted](/slides/php-java/documentproperties/getlastprinted/)() | Date | Returns the date when a presentation was printed last time. Read/write java.util.Date. |
| [getLastSavedBy](/slides/php-java/documentproperties/getlastsavedby/)() | String | Returns or sets the name of a last person who modified a presentation. Read/write String. |
| [getLastSavedTime](/slides/php-java/documentproperties/getlastsavedtime/)() | Date | Returns the date when a presentation was modified last time. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) method summary. |
| [getManager](/slides/php-java/documentproperties/getmanager/)() | String | Returns or sets the manager property. Read/write String. |
| [getNameOfApplication](/slides/php-java/documentproperties/getnameofapplication/)() | String | Returns or sets the name of the application. Read/write String. |
| [getPresentationFormat](/slides/php-java/documentproperties/getpresentationformat/)() | String | Returns or sets the intended format of a presentation. Read/write String. |
| [getRevisionNumber](/slides/php-java/documentproperties/getrevisionnumber/)() | int | Returns or sets the presentation revision number. Read/write int. |
| [getSharedDoc](/slides/php-java/documentproperties/getshareddoc/)() | boolean | Determines whether the presentation is shared between multiple people. Read/write boolean. |
| [getSubject](/slides/php-java/documentproperties/getsubject/)() | String | Returns or sets the subject of a presentation. Read/write String. |
| [getTitle](/slides/php-java/documentproperties/gettitle/)() | String | Returns or sets the title of a presentation. Read/write String. |
| [getTotalEditingTime](/slides/php-java/documentproperties/gettotaleditingtime/)() | double | Total editing time of a presentation. Read/write double. |
| [get_Item](/slides/php-java/documentproperties/get_item/)(String) | Object | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |
| [removeCustomProperty](/slides/php-java/documentproperties/removecustomproperty/)(String) | boolean | Remove a custom property associated with a specified name. |
| [setApplicationTemplate](/slides/php-java/documentproperties/setapplicationtemplate/)(String) | void | Returns or sets the template of a application. Read/write String. |
| [setAuthor](/slides/php-java/documentproperties/setauthor/)(String) | void | Returns or sets the author of a presentation. Read/write String. |
| [setCategory](/slides/php-java/documentproperties/setcategory/)(String) | void | Returns or sets the category of a presentation. Read/write String. |
| [setComments](/slides/php-java/documentproperties/setcomments/)(String) | void | Returns or sets the comments of a presentation. Read/write String. |
| [setCompany](/slides/php-java/documentproperties/setcompany/)(String) | void | Returns or sets the company property. Read/write String. |
| [setContentStatus](/slides/php-java/documentproperties/setcontentstatus/)(String) | void | Returns or sets the content status of a presentation. Read/write String. |
| [setContentType](/slides/php-java/documentproperties/setcontenttype/)(String) | void | Returns or sets the content type of a presentation. Read/write String. |
| [setCreatedTime](/slides/php-java/documentproperties/setcreatedtime/)(Date) | void | Returns the date when a presentation was created. Read/write java.util.Date. |
| [setCustomPropertyValue](/slides/php-java/documentproperties/setcustompropertyvalue/)(String, boolean) | void | Sets a named boolean custom property. |
| [setCustomPropertyValue](/slides/php-java/documentproperties/setcustompropertyvalue/)(String, int) | void | Sets a named integer custom property. |
| [setCustomPropertyValue](/slides/php-java/documentproperties/setcustompropertyvalue/)(String, Date) | void | Sets a named DateTime custom property. |
| [setCustomPropertyValue](/slides/php-java/documentproperties/setcustompropertyvalue/)(String, String) | void | Sets a named string custom property. |
| [setCustomPropertyValue](/slides/php-java/documentproperties/setcustompropertyvalue/)(String, float) | void | Sets a named float custom property. |
| [setCustomPropertyValue](/slides/php-java/documentproperties/setcustompropertyvalue/)(String, double) | void | Sets a named double custom property. |
| [setHyperlinkBase](/slides/php-java/documentproperties/sethyperlinkbase/)(String) | void | Returns or sets the HyperlinkBase document property. Read/write String. |
| [setKeywords](/slides/php-java/documentproperties/setkeywords/)(String) | void | Returns or sets the keywords of a presentation. Read/write String. |
| [setLastPrinted](/slides/php-java/documentproperties/setlastprinted/)(Date) | void | Returns the date when a presentation was printed last time. Read/write java.util.Date. |
| [setLastSavedBy](/slides/php-java/documentproperties/setlastsavedby/)(String) | void | Returns or sets the name of a last person who modified a presentation. Read/write String. |
| [setLastSavedTime](/slides/php-java/documentproperties/setlastsavedtime/)(Date) | void | Returns the date when a presentation was modified last time. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) method summary. |
| [setManager](/slides/php-java/documentproperties/setmanager/)(String) | void | Returns or sets the manager property. Read/write String. |
| [setNameOfApplication](/slides/php-java/documentproperties/setnameofapplication/)(String) | void | Returns or sets the name of the application. Read/write String. |
| [setPresentationFormat](/slides/php-java/documentproperties/setpresentationformat/)(String) | void | Returns or sets the intended format of a presentation. Read/write String. |
| [setRevisionNumber](/slides/php-java/documentproperties/setrevisionnumber/)(int) | void | Returns or sets the presentation revision number. Read/write int. |
| [setSharedDoc](/slides/php-java/documentproperties/setshareddoc/)(boolean) | void | Determines whether the presentation is shared between multiple people. Read/write boolean. |
| [setSubject](/slides/php-java/documentproperties/setsubject/)(String) | void | Returns or sets the subject of a presentation. Read/write String. |
| [setTitle](/slides/php-java/documentproperties/settitle/)(String) | void | Returns or sets the title of a presentation. Read/write String. |
| [setTotalEditingTime](/slides/php-java/documentproperties/settotaleditingtime/)(double) | void | Total editing time of a presentation. Read/write double. |
| [set_Item](/slides/php-java/documentproperties/set_item/)(String, Object) | void | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |
