---
title: IGradientStopCollection
second_title: Aspose.Slides for Android Java API 参考
description: 表示渐变停止点的集合。
type: docs
url: /zh/com.aspose.slides/igradientstopcollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

表示渐变停止点的集合。
## 方法

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根据索引返回渐变停止点。 |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | 创建新的渐变停止点并将其添加到集合末尾。 |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 创建新的渐变停止点并将其添加到集合末尾。 |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 创建新的渐变停止点并将其添加到集合末尾。 |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | 创建新的渐变停止点并将其插入到集合中指定的索引位置。 |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 创建新的渐变停止点并将其插入到集合中指定的索引位置。 |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 创建新的渐变停止点并将其插入到集合中指定的索引位置。 |
| [removeAt(int index)](#removeAt-int-) | 在指定索引处移除渐变停止点。 |
| [clear()](#clear--) | 从集合中移除所有渐变停止点。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

根据索引返回渐变停止点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

创建新的渐变停止点并将其添加到集合末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | float | 新渐变停止点的位置。 |
| color | java.lang.Integer | 新渐变停止点的颜色。 |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop) - 集合中新梯度停止点的索引。
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

创建新的渐变停止点并将其添加到集合末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | float | 新渐变停止点的位置。 |
| presetColor | int | 新渐变停止点的颜色。 |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop) - 集合中新梯度停止点的索引。
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

创建新的渐变停止点并将其添加到集合末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | float | 新渐变停止点的位置。 |
| schemeColor | int | 新渐变停止点的颜色。 |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop) - 集合中新梯度停止点的索引。
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

创建新的渐变停止点并将其插入到集合中指定的索引位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在集合中插入新渐变停止点的索引位置。 |
| position | float | 新渐变停止点的位置。 |
| color | java.lang.Integer | 新渐变停止点的颜色。 |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

创建新的渐变停止点并将其插入到集合中指定的索引位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在集合中插入新渐变停止点的索引位置。 |
| position | float | 新渐变停止点的位置。 |
| presetColor | int | 新渐变停止点的颜色。 |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

创建新的渐变停止点并将其插入到集合中指定的索引位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在集合中插入新渐变停止点的索引位置。 |
| position | float | 新渐变停止点的位置。 |
| schemeColor | int | 新渐变停止点的颜色。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

在指定索引处移除渐变停止点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应该被删除的渐变停止点的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

从集合中移除所有渐变停止点。