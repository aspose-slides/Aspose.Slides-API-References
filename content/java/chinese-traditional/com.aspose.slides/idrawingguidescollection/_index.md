---
title: IDrawingGuidesCollection
second_title: Aspose.Slides for Java API 參考文件
description: 表示可調整繪圖指南的集合。
type: docs
url: /zh-hant/com.aspose.slides/idrawingguidescollection/
---
**所有已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

表示可調整繪圖指南的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根據索引傳回繪圖指南。 |
| [add(byte orientation, float position)](#add-byte-float-) | 在集合的末端新增繪圖指南。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的繪圖指南。 |
| [clear()](#clear--) | 移除集合中的所有元素。 |
| [getCount()](#getCount--) | 取得集合中所有元素的數量。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

根據索引傳回繪圖指南。唯讀 [IDrawingGuide](../../com.aspose.slides/idrawingguide)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

在集合的末端新增繪圖指南。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| orientation | byte | 繪圖指南的方向。 |
| position | float | 繪圖指南的座標（以點為單位）。 |

**返回值：**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除指定索引處的繪圖指南。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 應刪除之繪圖指南的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

移除集合中的所有元素。

### getCount() {#getCount--}
```
public abstract int getCount()
```

取得集合中所有元素的數量。唯讀 int。

**返回值：**
int