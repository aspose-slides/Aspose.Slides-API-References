---
title: DocumentProperties
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/documentproperties/
---

## DocumentProperties class

 Represents properties of a presentation.
 
| [DocumentProperties]() | Initializes new instance of class DocumentProperties. |

### Result
DocumentProperties


---


| [clearBuiltInProperties] () | Clears and sets default values for all builtIn properties. |


---


| [clearCustomProperties] () | Removes all custom properties. |


---


| [cloneT] () | Clones current object |

### Result
[DocumentProperties]


---


| [containsCustomProperty] ([String]) | Check presents of a custom property with a specified name. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of a custom property to check. |

### Result
boolean


---


| [deepClone] () | Clones current object |

### Result
Object


---


| [getAppVersion] () | Returns the app version. Read-only String. |

### Result
String


---


| [getApplicationTemplate] () | Returns or sets the template of a application. Read/write String. |

### Result
String


---


| [getAuthor] () | Returns or sets the author of a presentation. Read/write String. |

### Result
String


---


| [getCategory] () | Returns or sets the category of a presentation. Read/write String. |

### Result
String


---


| [getComments] () | Returns or sets the comments of a presentation. Read/write String. |

### Result
String


---


| [getCompany] () | Returns or sets the company property. Read/write String. |

### Result
String


---


| [getContentStatus] () | Returns or sets the content status of a presentation. Read/write String. |

### Result
String


---


| [getContentType] () | Returns or sets the content type of a presentation. Read/write String. |

### Result
String


---


| [getCountOfCustomProperties] () | Returns the number of custom properties actually contained in a collection. Read-only int. |

### Result
int


---


| [getCreatedTime] () | Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date. |

### Result
Date


---


| [getCustomPropertyName] ([int]) | Return a custom property name at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index of a custom property to get. |

### Result
String

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | Index is less than zero. Index is equal to or greater than Count. |


---


| [getCustomPropertyValue] ([String], [boolean[]]) | Gets a named boolean value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to get |
| value | [boolean[]] | Custom property value |


---


| [getCustomPropertyValue] ([String], [int[]]) | Gets a named integer value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to get |
| value | [int[]] | Custom property value |


---


| [getCustomPropertyValue] ([String], [java.util.Date[]]) | Gets a named DateTime value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to get |
| value | [java.util.Date[]] | Custom property value |


---


| [getCustomPropertyValue] ([String], [java.lang.String[]]) | Gets a named string value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to get |
| value | [java.lang.String[]] | Custom property value |


---


| [getCustomPropertyValue] ([String], [float[]]) | Gets a named float value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to get |
| value | [float[]] | Custom property value |


---


| [getCustomPropertyValue] ([String], [double[]]) | Gets a named double value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to get. |
| value | [double[]] | Custom property value |


---


| [getHyperlinkBase] () | Returns or sets the HyperlinkBase document property. Read/write String. |

### Result
String


---


| [getKeywords] () | Returns or sets the keywords of a presentation. Read/write String. |

### Result
String


---


| [getLastPrinted] () | Returns the date when a presentation was printed last time. Read/write java.util.Date. |

### Result
Date


---


| [getLastSavedBy] () | Returns or sets the name of a last person who modified a presentation. Read/write String. |

### Result
String


---


| [getLastSavedTime] () | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by function IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) function summary. |

### Result
Date


---


| [getManager] () | Returns or sets the manager property. Read/write String. |

### Result
String


---


| [getNameOfApplication] () | Returns or sets the name of the application. Read/write String. |

### Result
String


---


| [getPresentationFormat] () | Returns or sets the intended format of a presentation. Read/write String. |

### Result
String


---


| [getRevisionNumber] () | Returns or sets the presentation revision number. Read/write int. |

### Result
int


---


| [getSharedDoc] () | Determines whether the presentation is shared between multiple people. Read/write boolean. |

### Result
boolean


---


| [getSubject] () | Returns or sets the subject of a presentation. Read/write String. |

### Result
String


---


| [getTitle] () | Returns or sets the title of a presentation. Read/write String. |

### Result
String


---


| [getTotalEditingTime] () | Total editing time of a presentation. Read/write double. |

### Result
double


---


| [get_Item] ([String]) | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |

### Result
Object


---


| [removeCustomProperty] ([String]) | Remove a custom property associated with a specified name. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of a custom property to remove. |

### Result
boolean


---


| [setApplicationTemplate] ([String]) | Returns or sets the template of a application. Read/write String. |


---


| [setAuthor] ([String]) | Returns or sets the author of a presentation. Read/write String. |


---


| [setCategory] ([String]) | Returns or sets the category of a presentation. Read/write String. |


---


| [setComments] ([String]) | Returns or sets the comments of a presentation. Read/write String. |


---


| [setCompany] ([String]) | Returns or sets the company property. Read/write String. |


---


| [setContentStatus] ([String]) | Returns or sets the content status of a presentation. Read/write String. |


---


| [setContentType] ([String]) | Returns or sets the content type of a presentation. Read/write String. |


---


| [setCreatedTime] ([Date]) | Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date. |


---


| [setCustomPropertyValue] ([String], [boolean]) | Sets a named boolean custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to set |
| value | [boolean] | Custom property value |


---


| [setCustomPropertyValue] ([String], [int]) | Sets a named integer custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to set |
| value | [int] | Custom property value |


---


| [setCustomPropertyValue] ([String], [Date]) | Sets a named DateTime custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to set |
| value | [Date] | Custom property value |


---


| [setCustomPropertyValue] ([String], [String]) | Sets a named string custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to set |
| value | [String] | Custom property value |


---


| [setCustomPropertyValue] ([String], [float]) | Sets a named float custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to set |
| value | [float] | Custom property value |


---


| [setCustomPropertyValue] ([String], [double]) | Sets a named double custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | [String] | Name of the custom property to set |
| value | [double] | Custom property value |


---


| [setHyperlinkBase] ([String]) | Returns or sets the HyperlinkBase document property. Read/write String. |


---


| [setKeywords] ([String]) | Returns or sets the keywords of a presentation. Read/write String. |


---


| [setLastPrinted] ([Date]) | Returns the date when a presentation was printed last time. Read/write java.util.Date. |


---


| [setLastSavedBy] ([String]) | Returns or sets the name of a last person who modified a presentation. Read/write String. |


---


| [setLastSavedTime] ([Date]) | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by function IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) function summary. |


---


| [setManager] ([String]) | Returns or sets the manager property. Read/write String. |


---


| [setNameOfApplication] ([String]) | Returns or sets the name of the application. Read/write String. |


---


| [setPresentationFormat] ([String]) | Returns or sets the intended format of a presentation. Read/write String. |


---


| [setRevisionNumber] ([int]) | Returns or sets the presentation revision number. Read/write int. |


---


| [setSharedDoc] ([boolean]) | Determines whether the presentation is shared between multiple people. Read/write boolean. |


---


| [setSubject] ([String]) | Returns or sets the subject of a presentation. Read/write String. |


---


| [setTitle] ([String]) | Returns or sets the title of a presentation. Read/write String. |


---


| [setTotalEditingTime] ([double]) | Total editing time of a presentation. Read/write double. |


---


| [set_Item] ([String], [Object]) | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |


---


