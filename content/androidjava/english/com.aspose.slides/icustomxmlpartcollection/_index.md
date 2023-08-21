---
title: ICustomXmlPartCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents collection of custom xml parts.
type: docs
url: /com.aspose.slides/icustomxmlpartcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Represents collection of custom xml parts.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the element at the specified index. |
| [add(byte[] xmlData)](#add-byte---) | Adds new custom xml part. |
| [add(String xmlString)](#add-java.lang.String-) | Adds new custom xml part. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Adds new custom xml part. |
| [removeAt(int index)](#removeAt-int-) | Removes custom xml part at the specified index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Removes the first occurrence of a specific object from the collection. |
| [clear()](#clear--) | Removes all items from the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```


Returns the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to get. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - The element at the specified index.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```


Adds new custom xml part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlData | byte[] | The xml data of new part to be added. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Created custom xml part.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```


Adds new custom xml part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlString | java.lang.String | The xml string of new part to be added. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Created custom xml part.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```


Adds new custom xml part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The inputStream with xml data of new part to be added. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Created custom xml part.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes custom xml part at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```


Removes the first occurrence of a specific object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | The custom xml part to remove. |

**Returns:**
boolean - true if item is successfully removed; otherwise, false.
### clear() {#clear--}
```
public abstract void clear()
```


Removes all items from the collection.

