---
title: IMasterSlideCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示主幻灯片的集合。
type: docs
url: /zh/com.aspose.slides/imasterslidecollection/
---
**已实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

表示主幻灯片的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | 从集合中移除特定对象的首次出现。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 移除未使用的主幻灯片。 |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 将指定主幻灯片的副本添加到集合末尾。 |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 将指定主幻灯片的副本插入到集合的指定位置。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```


获取指定索引处的元素。只读 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```


从集合中移除特定对象的首次出现。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要从集合中移除的主幻灯片。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除集合中指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的基于零的索引。 |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```


移除未使用的主幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ignorePreserveField | boolean | 确定即使其 [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) 属性设为 true，是否仍应移除未使用的主幻灯片。 |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```


将指定主幻灯片的副本添加到集合末尾。关联的布局幻灯片也会被复制。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的幻灯片。 |

**返回值:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已添加的幻灯片。
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


将在集合的指定位置插入指定主幻灯片的副本。关联的布局幻灯片也会被复制。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的幻灯片。 |

**返回值:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已插入的主幻灯片。