---
title: DocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description:  Represents properties of a presentation.
type: docs
weight: 157
url: /androidjava/com.aspose.slides/documentproperties/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Represents properties of a presentation.
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Initializes new instance of class [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Methods

| Method | Description |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Returns the app version. |
| [getNameOfApplication()](#getNameOfApplication--) | Returns or sets the name of the application. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Returns or sets the name of the application. |
| [getCompany()](#getCompany--) | Returns or sets the company property. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Returns or sets the company property. |
| [getManager()](#getManager--) | Returns or sets the manager property. |
| [setManager(String value)](#setManager-java.lang.String-) | Returns or sets the manager property. |
| [getPresentationFormat()](#getPresentationFormat--) | Returns or sets the intended format of a presentation. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Returns or sets the intended format of a presentation. |
| [getSharedDoc()](#getSharedDoc--) | Determines whether the presentation is shared between multiple people. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Determines whether the presentation is shared between multiple people. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Returns or sets the template of a application. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Returns or sets the template of a application. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Total editing time of a presentation. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Total editing time of a presentation. |
| [getTitle()](#getTitle--) | Returns or sets the title of a presentation. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Returns or sets the title of a presentation. |
| [getSubject()](#getSubject--) | Returns or sets the subject of a presentation. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Returns or sets the subject of a presentation. |
| [getAuthor()](#getAuthor--) | Returns or sets the author of a presentation. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Returns or sets the author of a presentation. |
| [getKeywords()](#getKeywords--) | Returns or sets the keywords of a presentation. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Returns or sets the keywords of a presentation. |
| [getComments()](#getComments--) | Returns or sets the comments of a presentation. |
| [setComments(String value)](#setComments-java.lang.String-) | Returns or sets the comments of a presentation. |
| [getCategory()](#getCategory--) | Returns or sets the category of a presentation. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Returns or sets the category of a presentation. |
| [getCreatedTime()](#getCreatedTime--) | Returns the date when a presentation was created. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Returns the date when a presentation was created. |
| [getLastSavedTime()](#getLastSavedTime--) | Returns the date when a presentation was modified last time. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Returns the date when a presentation was modified last time. |
| [getLastPrinted()](#getLastPrinted--) | Returns the date when a presentation was printed last time. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Returns the date when a presentation was printed last time. |
| [getLastSavedBy()](#getLastSavedBy--) | Returns or sets the name of a last person who modified a presentation. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Returns or sets the name of a last person who modified a presentation. |
| [getRevisionNumber()](#getRevisionNumber--) | Returns or sets the presentation revision number. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Returns or sets the presentation revision number. |
| [getContentStatus()](#getContentStatus--) | Returns or sets the content status of a presentation. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Returns or sets the content status of a presentation. |
| [getContentType()](#getContentType--) | Returns or sets the content type of a presentation. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Returns or sets the content type of a presentation. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Returns or sets the HyperlinkBase document property. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Returns or sets the HyperlinkBase document property. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Returns the number of custom properties actually contained in a collection. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Return a custom property name at the specified index. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Remove a custom property associated with a specified name. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Check presents of a custom property with a specified name. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returns or sets the custom property associated with a specified name. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Returns or sets the custom property associated with a specified name. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Sets a named boolean custom property. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Sets a named integer custom property. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Sets a named DateTime custom property. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Sets a named string custom property. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Sets a named float custom property. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Sets a named double custom property. |
| [clearCustomProperties()](#clearCustomProperties--) | Removes all custom properties. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Clears and sets default values for all builtIn properties. |
| [deepClone()](#deepClone--) | Clones current object |
| [cloneT()](#cloneT--) | Clones current object |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```


Initializes new instance of class [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```


Returns the app version. Read-only String.

**Returns:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```


Returns or sets the name of the application. Read/write String.

**Returns:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```


Returns or sets the name of the application. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Returns or sets the company property. Read/write String.

**Returns:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Returns or sets the company property. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```


Returns or sets the manager property. Read/write String.

**Returns:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```


Returns or sets the manager property. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```


Returns or sets the intended format of a presentation. Read/write String.

**Returns:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```


Returns or sets the intended format of a presentation. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```


Determines whether the presentation is shared between multiple people. Read/write boolean.

**Returns:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```


Determines whether the presentation is shared between multiple people. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```


Returns or sets the template of a application. Read/write String.

**Returns:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```


Returns or sets the template of a application. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```


Total editing time of a presentation. Read/write double.

**Returns:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```


Total editing time of a presentation. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Returns or sets the title of a presentation. Read/write String.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Returns or sets the title of a presentation. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Returns or sets the subject of a presentation. Read/write String.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Returns or sets the subject of a presentation. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Returns or sets the author of a presentation. Read/write String.

**Returns:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Returns or sets the author of a presentation. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```


Returns or sets the keywords of a presentation. Read/write String.

**Returns:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```


Returns or sets the keywords of a presentation. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Returns or sets the comments of a presentation. Read/write String.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Returns or sets the comments of a presentation. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```


Returns or sets the category of a presentation. Read/write String.

**Returns:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Returns or sets the category of a presentation. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


Returns the date when a presentation was created. Read/write java.util.Date.

**Returns:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Returns the date when a presentation was created. Read/write java.util.Date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```


Returns the date when a presentation was modified last time. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method [IPresentationInfo\#readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) Please see the example in [IPresentationInfo\#updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) method summary.

**Returns:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```


Returns the date when a presentation was modified last time. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method [IPresentationInfo\#readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) Please see the example in [IPresentationInfo\#updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) method summary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```


Returns the date when a presentation was printed last time. Read/write java.util.Date.

**Returns:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```


Returns the date when a presentation was printed last time. Read/write java.util.Date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```


Returns or sets the name of a last person who modified a presentation. Read/write String.

**Returns:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```


Returns or sets the name of a last person who modified a presentation. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```


Returns or sets the presentation revision number. Read/write int.

**Returns:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```


Returns or sets the presentation revision number. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```


Returns or sets the content status of a presentation. Read/write String.

**Returns:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```


Returns or sets the content status of a presentation. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Returns or sets the content type of a presentation. Read/write String.

**Returns:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Returns or sets the content type of a presentation. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```


Returns or sets the HyperlinkBase document property. Read/write String.

**Returns:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```


Returns or sets the HyperlinkBase document property. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```


Returns the number of custom properties actually contained in a collection. Read-only int.

**Returns:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```


Return a custom property name at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of a custom property to get. |

**Returns:**
java.lang.String - Custom property name at the specified index.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```


Remove a custom property associated with a specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of a custom property to remove. |

**Returns:**
boolean - Return true if a property was removed, false overwise.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```


Check presents of a custom property with a specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of a custom property to check. |

**Returns:**
boolean - Return true if property exists, false overwise.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```


Returns or sets the custom property associated with a specified name. Read/write Object.

--------------------

Value can be **int**, **float**, **String**, **boolean** or **Date**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```


Returns or sets the custom property associated with a specified name. Read/write Object.

--------------------

Value can be **int**, **float**, **String**, **boolean** or **Date**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```


Gets a named boolean value from the custom properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get |
| value | boolean[] | Custom property value |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```


Gets a named integer value from the custom properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get |
| value | int[] | Custom property value |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```


Gets a named DateTime value from the custom properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get |
| value | java.util.Date[] | Custom property value |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```


Gets a named string value from the custom properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get |
| value | java.lang.String[] | Custom property value |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```


Gets a named float value from the custom properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get |
| value | float[] | Custom property value |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```


Gets a named double value from the custom properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get. |
| value | double[] | Custom property value |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```


Sets a named boolean custom property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | boolean | Custom property value |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```


Sets a named integer custom property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | int | Custom property value |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```


Sets a named DateTime custom property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | java.util.Date | Custom property value |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```


Sets a named string custom property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | java.lang.String | Custom property value |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```


Sets a named float custom property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | float | Custom property value |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```


Sets a named double custom property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | double | Custom property value |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```


Removes all custom properties.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```


Clears and sets default values for all builtIn properties.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clones current object

**Returns:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```


Clones current object

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone
