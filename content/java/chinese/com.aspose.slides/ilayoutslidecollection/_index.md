---
title: ILayoutSlideCollection
second_title: Aspose.Slides Java API 参考
description: 表示布局幻灯片集合的基类。
type: docs
url: /zh/com.aspose.slides/ilayoutslidecollection/
---
**实现的所有接口:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

表示布局幻灯片集合的基类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回索引处的布局幻灯片。 |
| [getByType(byte type)](#getByType-byte-) | 返回指定类型的第一个布局幻灯片。 |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | 从集合中移除布局。 |
| [removeUnused()](#removeUnused--) | 移除未使用的布局幻灯片（HasDependingSlides 为 false 的布局幻灯片）。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

返回索引处的布局幻灯片。只读 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

返回指定类型的第一个布局幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | byte | 要查找的布局幻灯片类型。 |

**返回:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide)，如果未找到布局则为 null。

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

从集合中移除布局。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要从集合中移除的布局幻灯片。 |

--------------------

1) 为避免抛出 PptxEditException，请先检查布局的 HasDependingSlides 属性。 2) 还可以使用 [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) 方法来简化代码。 |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

移除未使用的布局幻灯片（HasDependingSlides 为 false 的布局幻灯片）。