---
title: ISensitivityLabelCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of sensitivity labels applied to the document.
type: docs
url: /com.aspose.slides/isensitivitylabelcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Represents a collection of sensitivity labels applied to the document.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the sensitivity label by index. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Adds the sensitivity label at the end of the collection. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Adds a SensitivityLabel to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the sensitivity label at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [getCount()](#getCount--) | Gets the number of all elements in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```


Returns the sensitivity label by index. Read-only [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Adds the sensitivity label at the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The id of sensitivity label. |
| siteId | java.util.UUID | The Azure Active Directory (Azure AD) site identifier. |
| isEnabled | boolean | Flag indicates whether the sensitivity label is enabled. |
| methodType | int | The assignment method for the sensitivity label. |

**Returns:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```


Adds a SensitivityLabel to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | The SensitivityLabel object to be added at the end of the collection. |

**Returns:**
int - The index at which the SensitivityLabel was added.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the sensitivity label at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the sensitivity label that should be deleted. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all elements from the collection.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of all elements in the collection. Read-only  int .

**Returns:**
int
