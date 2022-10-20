---
title: IVbaModuleCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of a VBA Project modules.
type: docs
weight: 1088
url: /androidjava/com.aspose.slides/ivbamodulecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Represents a collection of a VBA Project modules.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Adds a new empty module to the VBA Project. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Removes the first occurrence of a specific object from the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


Adds a new empty module to the VBA Project.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the module |

**Returns:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Added module.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


Removes the first occurrence of a specific object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | The module to remove from the collection. |

