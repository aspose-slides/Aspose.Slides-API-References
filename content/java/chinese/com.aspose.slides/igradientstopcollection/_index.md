---
title: IGradientStopCollection
second_title: Aspose.Slides for Java API 参考
description: 表示一组渐变停止点。
type: docs
url: /zh/com.aspose.slides/igradientstopcollection/
---
**所有已实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

表示一组渐变停止点。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 按索引返回渐变停止点。 |
| [add(float position, Color color)](#add-float-java.awt.Color-) | 创建新的渐变停止点并将其添加到集合的末尾。 |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 创建新的渐变停止点并将其添加到集合的末尾。 |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 创建新的渐变停止点并将其添加到集合的末尾。 |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | 创建新的渐变停止点并在指定索引处插入到集合中。 |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 创建新的渐变停止点并在指定索引处插入到集合中。 |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 创建新的渐变停止点并在指定索引处插入到集合中。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的渐变停止点。 |
| [clear()](#clear--) | 删除集合中的所有渐变停止点。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

按索引返回渐变停止点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

创建新的渐变停止点并将其添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | float | 新渐变停止点的位置。 |
| color | java.awt.Color | 新渐变停止点的颜色。 |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop) - 集合中新渐变停止点的索引。

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

创建新的渐变停止点并将其添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | float | 新渐变停止点的位置。 |
| presetColor | int | 新渐变停止点的颜色。 |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop) - 集合中新渐变停止点的索引。

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

创建新的渐变停止点并将其添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | float | 新渐变停止点的位置。 |
| schemeColor | int | 新渐变停止点的颜色。 |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop) - 集合中新渐变停止点的索引。

### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

创建新的渐变停止点并在指定索引处插入到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 将在集合中插入新渐变停止点的索引。 |
| position | float | 新渐变停止点的位置。 |
| color | java.awt.Color | 新渐变停止点的颜色。 |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

创建新的渐变停止点并在指定索引处插入到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 将在集合中插入新渐变停止点的索引。 |
| position | float | 新渐变停止点的位置。 |
| presetColor | int | 新渐变停止点的颜色。 |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

创建新的渐变停止点并在指定索引处插入到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 将在集合中插入新渐变停止点的索引。 |
| position | float | 新渐变停止点的位置。 |
| schemeColor | int | 新渐变停止点的颜色。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

删除指定索引处的渐变停止点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的渐变停止点的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

删除集合中的所有渐变停止点。