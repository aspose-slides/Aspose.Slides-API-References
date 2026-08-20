---
title: ShapeElement
second_title: Aspose.Slides Java API 參考
description: 表示具有相同輪廓和填充屬性的形狀的一部分。
type: docs
url: /zh-hant/com.aspose.slides/shapeelement/
---
**繼承:**
java.lang.Object

**全部已實作介面:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

表示具有相同輪廓和填充屬性的形狀的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getParentShape()](#getParentShape--) | 返回建立此元素的 Shape\_PPT。 |
| [getPathPoints()](#getPathPoints--) | 取得定義元素路徑幾何形狀的點陣列。 |
| [getPathTypes()](#getPathTypes--) | 取得指定元素路徑中每個點類型的位元組值陣列。 |
| [getFillSource()](#getFillSource--) | 返回有關如何填充元素的資訊。 |
| [getStrokeSource()](#getStrokeSource--) | 返回有關如何描邊元素的資訊。 |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


返回建立此元素的 Shape\_PPT。唯讀 [Shape](../../com.aspose.slides/shape)。

**返回:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```


取得定義元素路徑幾何形狀的點陣列。

**返回:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


取得指定元素路徑中每個點類型的位元組值陣列。

**0** 表示該點是圖形的起點。

**1** 表示該點是線段的兩個端點之一。

**3** 表示該點是三次貝茲曲線的端點或控制點。

**7** 掩碼除最低三位外的所有位元，這三位指示點的類型。

**16** 指定相應的線段為虛線。

**32** 指定該點為標記。

**128** 指定該點是閉合子路徑（圖形）的最後一點。

**129** 表示同時為線段端點且為閉合子路徑最後一點的資料點。

**返回:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


返回有關如何填充元素的資訊。唯讀 [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource)。

**返回:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


返回有關如何描邊元素的資訊。唯讀 [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource)。

**返回:**
byte