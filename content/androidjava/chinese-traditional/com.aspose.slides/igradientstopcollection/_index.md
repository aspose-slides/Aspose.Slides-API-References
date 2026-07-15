---
title: IGradientStopCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示一個漸層停止點的集合。
type: docs
url: /zh-hant/com.aspose.slides/igradientstopcollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

表示一個漸層停止點的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引的漸層停止點。 |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | 建立新的漸層停止點並將其加入集合的末端。 |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 建立新的漸層停止點並將其加入集合的末端。 |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 建立新的漸層停止點並將其加入集合的末端。 |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | 建立新的漸層停止點並將其插入集合中指定的索引。 |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 建立新的漸層停止點並將其插入集合中指定的索引。 |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 建立新的漸層停止點並將其插入集合中指定的索引。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引的漸層停止點。 |
| [clear()](#clear--) | 移除集合中的所有漸層停止點。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

傳回指定索引的漸層停止點。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

建立新的漸層停止點並將其加入集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | float | 新漸層停止點的位置。 |
| color | java.lang.Integer | 新漸層停止點的顏色。 |

**傳回值:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 該集合中新漸層停止點的索引。
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

建立新的漸層停止點並將其加入集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | float | 新漸層停止點的位置。 |
| presetColor | int | 新漸層停止點的顏色。 |

**傳回值:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 該集合中新漸層停止點的索引。
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

建立新的漸層停止點並將其加入集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | float | 新漸層停止點的位置。 |
| schemeColor | int | 新漸層停止點的顏色。 |

**傳回值:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 該集合中新漸層停止點的索引。
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

建立新的漸層停止點並將其插入集合中指定的索引。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 集合中將插入新漸層停止點的索引。 |
| position | float | 新漸層停止點的位置。 |
| color | java.lang.Integer | 新漸層停止點的顏色。 |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

建立新的漸層停止點並將其插入集合中指定的索引。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 集合中將插入新漸層停止點的索引。 |
| position | float | 新漸層停止點的位置。 |
| presetColor | int | 新漸層停止點的顏色。 |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

建立新的漸層停止點並將其插入集合中指定的索引。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 集合中將插入新漸層停止點的索引。 |
| position | float | 新漸層停止點的位置。 |
| schemeColor | int | 新漸層停止點的顏色。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除指定索引的漸層停止點。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 應刪除的漸層停止點的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

移除集合中的所有漸層停止點。