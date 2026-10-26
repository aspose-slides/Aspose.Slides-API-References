---
title: ShapeElement
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示形狀中輪廓與填充屬性相同的部分。
type: docs
url: /zh-hant/com.aspose.slides/shapeelement/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)  
```
public class ShapeElement implements IShapeElement
```

表示形狀中輪廓與填充屬性相同的部分。

## 方法

| Method | Description |
| --- | --- |
| [getParentShape()](#getParentShape--) | 返回一個 Shape_PPT，該元素是為其創建的。 |
| [getPathPoints()](#getPathPoints--) | 獲取定義元素路徑幾何形狀的點陣列。 |
| [getPathTypes()](#getPathTypes--) | 獲取指定元素路徑中每個點類型的位元組值陣列。 |
| [getFillSource()](#getFillSource--) | 返回有關如何填充元素的信息。 |
| [getStrokeSource()](#getStrokeSource--) | 返回有關如何描邊元素的信息。 |

### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

返回一個 Shape_PPT，該元素是為其創建的。唯讀 [Shape](../../com.aspose.slides/shape)。

**返回:**  
[Shape](../../com.aspose.slides/shape)

### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

獲取定義元素路徑幾何形狀的點陣列。

**返回:**  
android.graphics.PointF[]

### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

獲取指定元素路徑中每個點類型的位元組值陣列。

**0** 表示該點是圖形的起點。

**1** 表示該點是線段的兩個端點之一。

**3** 表示該點是三次貝茲曲線的端點或控制點。

**7** 掩碼所有位元，僅保留低三位以指示點類型。

**16** 指定相應段為虛線。

**32** 指定該點為標記。

**128** 指定該點是封閉子路徑（圖形）中的最後一點。

**129** 表示該資料點同時是線段端點且是封閉子路徑的最後一點。

**返回:**  
byte[]

### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

返回有關如何填充元素的信息。唯讀 [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource)。

**返回:**  
byte

### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

返回有關如何描邊元素的信息。唯讀 [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource)。

**返回:**  
byte