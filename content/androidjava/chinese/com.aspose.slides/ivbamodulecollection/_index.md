---
title: IVbaModuleCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 VBA 项目模块的集合。
type: docs
url: /zh/com.aspose.slides/ivbamodulecollection/
---
**所有实现的接口:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

表示 VBA 项目模块的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | 向 VBA 项目添加一个新的空模块。 |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | 从集合中移除第一次出现的特定对象。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


获取指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


向 VBA 项目添加一个新的空模块。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 模块的名称 |

**返回值:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - 已添加的模块。
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


从集合中移除第一次出现的特定对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | 要从集合中移除的模块。 |