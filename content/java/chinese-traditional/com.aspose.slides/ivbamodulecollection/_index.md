---
title: IVbaModuleCollection
second_title: Aspose.Slides for Java API 參考
description: 表示 VBA Project 模組的集合。
type: docs
url: /zh-hant/com.aspose.slides/ivbamodulecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

表示 VBA Project 模組的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | 新增一個空的模組到 VBA Project。 |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | 從集合中移除特定物件的第一個出現。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


取得指定索引處的元素。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


新增一個空的模組到 VBA Project。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 模組的名稱 |

**傳回值：**
[IVbaModule](../../com.aspose.slides/ivbamodule) - 已新增的模組。
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


從集合中移除特定物件的第一個出現。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | 要從集合中移除的模組。 |