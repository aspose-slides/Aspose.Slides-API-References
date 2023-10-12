---
title: DocumentProperties
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/documentproperties/
---

## DocumentProperties class

 Represents properties of a presentation.
 
| Name | Description |
| --- | --- |
| DocumentProperties() | Initializes new instance of class DocumentProperties. |

### Result
DocumentProperties


---


| Name | Description |
| --- | --- |
| clearBuiltInProperties () | Clears and sets default values for all builtIn properties. |


---


| Name | Description |
| --- | --- |
| clearCustomProperties () | Removes all custom properties. |


---


| Name | Description |
| --- | --- |
| cloneT () | Clones current object |

### Result
DocumentProperties(../../documentproperties)


---


| Name | Description |
| --- | --- |
| containsCustomProperty (String) | Check presents of a custom property with a specified name. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of a custom property to check. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| deepClone () | Clones current object |

### Result
Object


---


| Name | Description |
| --- | --- |
| getAppVersion () | Returns the app version. Read-only String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getApplicationTemplate () | Returns or sets the template of a application. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getAuthor () | Returns or sets the author of a presentation. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getCategory () | Returns or sets the category of a presentation. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getComments () | Returns or sets the comments of a presentation. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getCompany () | Returns or sets the company property. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getContentStatus () | Returns or sets the content status of a presentation. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getContentType () | Returns or sets the content type of a presentation. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getCountOfCustomProperties () | Returns the number of custom properties actually contained in a collection. Read-only int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getCreatedTime () | Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date. |

### Result
Date


---


| Name | Description |
| --- | --- |
| getCustomPropertyName (int) | Return a custom property name at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of a custom property to get. |

### Result
String

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | Index is less than zero. Index is equal to or greater than Count. |


---


| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, boolean[]) | Gets a named boolean value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | boolean[] | Custom property value |


---


| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, int[]) | Gets a named integer value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | int[] | Custom property value |


---


| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, java.util.Date[]) | Gets a named DateTime value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | java.util.Date[] | Custom property value |


---


| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, java.lang.String[]) | Gets a named string value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | java.lang.String[] | Custom property value |


---


| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, float[]) | Gets a named float value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | float[] | Custom property value |


---


| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, double[]) | Gets a named double value from the custom properties. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get. |
| value | double[] | Custom property value |


---


| Name | Description |
| --- | --- |
| getHyperlinkBase () | Returns or sets the HyperlinkBase document property. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getKeywords () | Returns or sets the keywords of a presentation. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getLastPrinted () | Returns the date when a presentation was printed last time. Read/write java.util.Date. |

### Result
Date


---


| Name | Description |
| --- | --- |
| getLastSavedBy () | Returns or sets the name of a last person who modified a presentation. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getLastSavedTime () | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by function IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) function summary. |

### Result
Date


---


| Name | Description |
| --- | --- |
| getManager () | Returns or sets the manager property. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getNameOfApplication () | Returns or sets the name of the application. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getPresentationFormat () | Returns or sets the intended format of a presentation. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getRevisionNumber () | Returns or sets the presentation revision number. Read/write int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getSharedDoc () | Determines whether the presentation is shared between multiple people. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getSubject () | Returns or sets the subject of a presentation. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getTitle () | Returns or sets the title of a presentation. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getTotalEditingTime () | Total editing time of a presentation. Read/write double. |

### Result
double


---


| Name | Description |
| --- | --- |
| get_Item (String) | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |

### Result
Object


---


| Name | Description |
| --- | --- |
| removeCustomProperty (String) | Remove a custom property associated with a specified name. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of a custom property to remove. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| setApplicationTemplate (String) | Returns or sets the template of a application. Read/write String. |


---


| Name | Description |
| --- | --- |
| setAuthor (String) | Returns or sets the author of a presentation. Read/write String. |


---


| Name | Description |
| --- | --- |
| setCategory (String) | Returns or sets the category of a presentation. Read/write String. |


---


| Name | Description |
| --- | --- |
| setComments (String) | Returns or sets the comments of a presentation. Read/write String. |


---


| Name | Description |
| --- | --- |
| setCompany (String) | Returns or sets the company property. Read/write String. |


---


| Name | Description |
| --- | --- |
| setContentStatus (String) | Returns or sets the content status of a presentation. Read/write String. |


---


| Name | Description |
| --- | --- |
| setContentType (String) | Returns or sets the content type of a presentation. Read/write String. |


---


| Name | Description |
| --- | --- |
| setCreatedTime (Date) | Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date. |


---


| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, boolean) | Sets a named boolean custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | boolean | Custom property value |


---


| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, int) | Sets a named integer custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | int | Custom property value |


---


| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, Date) | Sets a named DateTime custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | Date | Custom property value |


---


| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, String) | Sets a named string custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | String | Custom property value |


---


| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, float) | Sets a named float custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | float | Custom property value |


---


| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, double) | Sets a named double custom property. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | double | Custom property value |


---


| Name | Description |
| --- | --- |
| setHyperlinkBase (String) | Returns or sets the HyperlinkBase document property. Read/write String. |


---


| Name | Description |
| --- | --- |
| setKeywords (String) | Returns or sets the keywords of a presentation. Read/write String. |


---


| Name | Description |
| --- | --- |
| setLastPrinted (Date) | Returns the date when a presentation was printed last time. Read/write java.util.Date. |


---


| Name | Description |
| --- | --- |
| setLastSavedBy (String) | Returns or sets the name of a last person who modified a presentation. Read/write String. |


---


| Name | Description |
| --- | --- |
| setLastSavedTime (Date) | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by function IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) function summary. |


---


| Name | Description |
| --- | --- |
| setManager (String) | Returns or sets the manager property. Read/write String. |


---


| Name | Description |
| --- | --- |
| setNameOfApplication (String) | Returns or sets the name of the application. Read/write String. |


---


| Name | Description |
| --- | --- |
| setPresentationFormat (String) | Returns or sets the intended format of a presentation. Read/write String. |


---


| Name | Description |
| --- | --- |
| setRevisionNumber (int) | Returns or sets the presentation revision number. Read/write int. |


---


| Name | Description |
| --- | --- |
| setSharedDoc (boolean) | Determines whether the presentation is shared between multiple people. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setSubject (String) | Returns or sets the subject of a presentation. Read/write String. |


---


| Name | Description |
| --- | --- |
| setTitle (String) | Returns or sets the title of a presentation. Read/write String. |


---


| Name | Description |
| --- | --- |
| setTotalEditingTime (double) | Total editing time of a presentation. Read/write double. |


---


| Name | Description |
| --- | --- |
| set_Item (String, Object) | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |


---


