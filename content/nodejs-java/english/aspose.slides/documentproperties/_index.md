---
title: DocumentProperties
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/documentproperties/
---

## DocumentProperties class

 Represents properties of a presentation.
 
### DocumentProperties {#DocumentProperties}

| Name | Description |
| --- | --- |
| DocumentProperties() | Initializes new instance of class DocumentProperties. |

 **Result**
DocumentProperties


---


### clearBuiltInProperties {#clearBuiltInProperties}

| Name | Description |
| --- | --- |
| clearBuiltInProperties () | Clears and sets default values for all builtIn properties. |


---


### clearCustomProperties {#clearCustomProperties}

| Name | Description |
| --- | --- |
| clearCustomProperties () | Removes all custom properties. |


---


### cloneT {#cloneT}

| Name | Description |
| --- | --- |
| cloneT () | Clones current object |

 **Result**
[DocumentProperties](../documentproperties)


---


### containsCustomProperty {#containsCustomProperty}

| Name | Description |
| --- | --- |
| containsCustomProperty (String) | Check presents of a custom property with a specified name. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of a custom property to check. |

 **Result**
boolean


---


### deepClone {#deepClone}

| Name | Description |
| --- | --- |
| deepClone () | Clones current object |

 **Result**
Object


---


### getAppVersion {#getAppVersion}

| Name | Description |
| --- | --- |
| getAppVersion () | Returns the app version. Read-only String. |

 **Result**
String


---


### getApplicationTemplate {#getApplicationTemplate}

| Name | Description |
| --- | --- |
| getApplicationTemplate () | Returns or sets the template of a application. Read/write String. |

 **Result**
String


---


### getAuthor {#getAuthor}

| Name | Description |
| --- | --- |
| getAuthor () | Returns or sets the author of a presentation. Read/write String. |

 **Result**
String


---


### getCategory {#getCategory}

| Name | Description |
| --- | --- |
| getCategory () | Returns or sets the category of a presentation. Read/write String. |

 **Result**
String


---


### getComments {#getComments}

| Name | Description |
| --- | --- |
| getComments () | Returns or sets the comments of a presentation. Read/write String. |

 **Result**
String


---


### getCompany {#getCompany}

| Name | Description |
| --- | --- |
| getCompany () | Returns or sets the company property. Read/write String. |

 **Result**
String


---


### getContentStatus {#getContentStatus}

| Name | Description |
| --- | --- |
| getContentStatus () | Returns or sets the content status of a presentation. Read/write String. |

 **Result**
String


---


### getContentType {#getContentType}

| Name | Description |
| --- | --- |
| getContentType () | Returns or sets the content type of a presentation. Read/write String. |

 **Result**
String


---


### getCountOfCustomProperties {#getCountOfCustomProperties}

| Name | Description |
| --- | --- |
| getCountOfCustomProperties () | Returns the number of custom properties actually contained in a collection. Read-only int. |

 **Result**
int


---


### getCreatedTime {#getCreatedTime}

| Name | Description |
| --- | --- |
| getCreatedTime () | Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date. |

 **Result**
Date


---


### getCustomPropertyName {#getCustomPropertyName}

| Name | Description |
| --- | --- |
| getCustomPropertyName (int) | Return a custom property name at the specified index. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of a custom property to get. |

 **Result**
String

 **Error**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | Index is less than zero. Index is equal to or greater than Count. |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, boolean[]) | Gets a named boolean value from the custom properties. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | boolean[] | Custom property value |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, int[]) | Gets a named integer value from the custom properties. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | int[] | Custom property value |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, java.util.Date[]) | Gets a named DateTime value from the custom properties. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | java.util.Date[] | Custom property value |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, java.lang.String[]) | Gets a named string value from the custom properties. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | java.lang.String[] | Custom property value |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, float[]) | Gets a named float value from the custom properties. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | float[] | Custom property value |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, double[]) | Gets a named double value from the custom properties. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get. |
| value | double[] | Custom property value |


---


### getHyperlinkBase {#getHyperlinkBase}

| Name | Description |
| --- | --- |
| getHyperlinkBase () | Returns or sets the HyperlinkBase document property. Read/write String. |

 **Result**
String


---


### getKeywords {#getKeywords}

| Name | Description |
| --- | --- |
| getKeywords () | Returns or sets the keywords of a presentation. Read/write String. |

 **Result**
String


---


### getLastPrinted {#getLastPrinted}

| Name | Description |
| --- | --- |
| getLastPrinted () | Returns the date when a presentation was printed last time. Read/write java.util.Date. |

 **Result**
Date


---


### getLastSavedBy {#getLastSavedBy}

| Name | Description |
| --- | --- |
| getLastSavedBy () | Returns or sets the name of a last person who modified a presentation. Read/write String. |

 **Result**
String


---


### getLastSavedTime {#getLastSavedTime}

| Name | Description |
| --- | --- |
| getLastSavedTime () | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by function IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) function summary. |

 **Result**
Date


---


### getManager {#getManager}

| Name | Description |
| --- | --- |
| getManager () | Returns or sets the manager property. Read/write String. |

 **Result**
String


---


### getNameOfApplication {#getNameOfApplication}

| Name | Description |
| --- | --- |
| getNameOfApplication () | Returns or sets the name of the application. Read/write String. |

 **Result**
String


---


### getPresentationFormat {#getPresentationFormat}

| Name | Description |
| --- | --- |
| getPresentationFormat () | Returns or sets the intended format of a presentation. Read/write String. |

 **Result**
String


---


### getRevisionNumber {#getRevisionNumber}

| Name | Description |
| --- | --- |
| getRevisionNumber () | Returns or sets the presentation revision number. Read/write int. |

 **Result**
int


---


### getSharedDoc {#getSharedDoc}

| Name | Description |
| --- | --- |
| getSharedDoc () | Determines whether the presentation is shared between multiple people. Read/write boolean. |

 **Result**
boolean


---


### getSubject {#getSubject}

| Name | Description |
| --- | --- |
| getSubject () | Returns or sets the subject of a presentation. Read/write String. |

 **Result**
String


---


### getTitle {#getTitle}

| Name | Description |
| --- | --- |
| getTitle () | Returns or sets the title of a presentation. Read/write String. |

 **Result**
String


---


### getTotalEditingTime {#getTotalEditingTime}

| Name | Description |
| --- | --- |
| getTotalEditingTime () | Total editing time of a presentation. Read/write double. |

 **Result**
double


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (String) | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |

 **Result**
Object


---


### removeCustomProperty {#removeCustomProperty}

| Name | Description |
| --- | --- |
| removeCustomProperty (String) | Remove a custom property associated with a specified name. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of a custom property to remove. |

 **Result**
boolean


---


### setApplicationTemplate {#setApplicationTemplate}

| Name | Description |
| --- | --- |
| setApplicationTemplate (String) | Returns or sets the template of a application. Read/write String. |


---


### setAuthor {#setAuthor}

| Name | Description |
| --- | --- |
| setAuthor (String) | Returns or sets the author of a presentation. Read/write String. |


---


### setCategory {#setCategory}

| Name | Description |
| --- | --- |
| setCategory (String) | Returns or sets the category of a presentation. Read/write String. |


---


### setComments {#setComments}

| Name | Description |
| --- | --- |
| setComments (String) | Returns or sets the comments of a presentation. Read/write String. |


---


### setCompany {#setCompany}

| Name | Description |
| --- | --- |
| setCompany (String) | Returns or sets the company property. Read/write String. |


---


### setContentStatus {#setContentStatus}

| Name | Description |
| --- | --- |
| setContentStatus (String) | Returns or sets the content status of a presentation. Read/write String. |


---


### setContentType {#setContentType}

| Name | Description |
| --- | --- |
| setContentType (String) | Returns or sets the content type of a presentation. Read/write String. |


---


### setCreatedTime {#setCreatedTime}

| Name | Description |
| --- | --- |
| setCreatedTime (Date) | Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date. |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, boolean) | Sets a named boolean custom property. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | boolean | Custom property value |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, int) | Sets a named integer custom property. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | int | Custom property value |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, Date) | Sets a named DateTime custom property. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | Date | Custom property value |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, String) | Sets a named string custom property. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | String | Custom property value |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, float) | Sets a named float custom property. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | float | Custom property value |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, double) | Sets a named double custom property. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | double | Custom property value |


---


### setHyperlinkBase {#setHyperlinkBase}

| Name | Description |
| --- | --- |
| setHyperlinkBase (String) | Returns or sets the HyperlinkBase document property. Read/write String. |


---


### setKeywords {#setKeywords}

| Name | Description |
| --- | --- |
| setKeywords (String) | Returns or sets the keywords of a presentation. Read/write String. |


---


### setLastPrinted {#setLastPrinted}

| Name | Description |
| --- | --- |
| setLastPrinted (Date) | Returns the date when a presentation was printed last time. Read/write java.util.Date. |


---


### setLastSavedBy {#setLastSavedBy}

| Name | Description |
| --- | --- |
| setLastSavedBy (String) | Returns or sets the name of a last person who modified a presentation. Read/write String. |


---


### setLastSavedTime {#setLastSavedTime}

| Name | Description |
| --- | --- |
| setLastSavedTime (Date) | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by function IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) function summary. |


---


### setManager {#setManager}

| Name | Description |
| --- | --- |
| setManager (String) | Returns or sets the manager property. Read/write String. |


---


### setNameOfApplication {#setNameOfApplication}

| Name | Description |
| --- | --- |
| setNameOfApplication (String) | Returns or sets the name of the application. Read/write String. |


---


### setPresentationFormat {#setPresentationFormat}

| Name | Description |
| --- | --- |
| setPresentationFormat (String) | Returns or sets the intended format of a presentation. Read/write String. |


---


### setRevisionNumber {#setRevisionNumber}

| Name | Description |
| --- | --- |
| setRevisionNumber (int) | Returns or sets the presentation revision number. Read/write int. |


---


### setSharedDoc {#setSharedDoc}

| Name | Description |
| --- | --- |
| setSharedDoc (boolean) | Determines whether the presentation is shared between multiple people. Read/write boolean. |


---


### setSubject {#setSubject}

| Name | Description |
| --- | --- |
| setSubject (String) | Returns or sets the subject of a presentation. Read/write String. |


---


### setTitle {#setTitle}

| Name | Description |
| --- | --- |
| setTitle (String) | Returns or sets the title of a presentation. Read/write String. |


---


### setTotalEditingTime {#setTotalEditingTime}

| Name | Description |
| --- | --- |
| setTotalEditingTime (double) | Total editing time of a presentation. Read/write double. |


---


### set_Item {#set_Item}

| Name | Description |
| --- | --- |
| set_Item (String, Object) | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |


---


