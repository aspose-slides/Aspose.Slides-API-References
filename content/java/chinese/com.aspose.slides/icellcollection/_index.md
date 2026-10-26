---
title: ICellCollection
second_title: Aspose.Slides Java API 参考
description: 表示一个单元格集合。
type: docs
url: /zh/com.aspose.slides/icellcollection/
---
**所有实现的接口:**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection  
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

表示一个单元格集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定位置的单元格。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

返回指定位置的单元格。只读 [ICell](../../com.aspose.slides/icell)。

--------------------

如果单元格被合并，则一个 CellEx 对象可能对应多个索引。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**  
[ICell](../../com.aspose.slides/icell)