---
title: SensitivityLabelCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of sensitivity labels applied to the document.
type: docs
url: /com.aspose.slides/sensitivitylabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
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
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [getCount()](#getCount--) | Returns the number of elements in the collection. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Copies all elements from the collection to the specified array. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Returns the sensitivity label by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
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
public final int add(ISensitivityLabel label)
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
public final void removeAt(int index)
```


Removes the sensitivity label at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the sensitivity label that should be deleted. |

### clear() {#clear--}
```
public final void clear()
```


Removes all elements from the collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - A  System.Collections.Generic.IEnumerator1  that can be used to iterate through the collection.
### getCount() {#getCount--}
```
public final int getCount()
```


Returns the number of elements in the collection. Read-only  int .

**Returns:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Copies all elements from the collection to the specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Target array. |
| index | int | Starting index in the target array. |

