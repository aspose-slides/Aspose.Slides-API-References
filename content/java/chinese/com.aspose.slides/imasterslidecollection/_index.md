---
title: IMasterSlideCollection
second_title: Aspose.Slides for Java API 参考
description: 表示母版幻灯片的集合。
type: docs
url: /zh/com.aspose.slides/imasterslidecollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

表示母版幻灯片的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | 从集合中移除特定对象的第一次出现。 |
| [removeAt(int index)](#removeAt-int-) | 从集合中移除指定索引处的元素。 |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 移除未使用的母版幻灯片。 |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 向集合末尾添加指定母版幻灯片的副本。 |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 在集合的指定位置插入指定母版幻灯片的副本。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

获取指定索引处的元素。只读 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IMasterSlide](../../com.aspose.slides/imasterslide)

### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

从集合中移除特定对象的第一次出现。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要从集合中移除的母版幻灯片。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

从集合中移除指定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

移除未使用的母版幻灯片。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ignorePreserveField | boolean | 确定即使其 [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) 属性设置为 true，是否仍应删除未使用的母版。 |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

向集合末尾添加指定母版幻灯片的副本。关联的布局幻灯片也会被复制。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的幻灯片。 |

**返回值：**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已添加的幻灯片。

### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

在集合的指定位置插入指定母版幻灯片的副本。关联的布局幻灯片也会被复制。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的幻灯片。 |

**返回值：**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已插入的母版幻灯片。