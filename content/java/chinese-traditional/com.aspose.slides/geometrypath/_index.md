---
title: GeometryPath
second_title: Aspose.Slides Java API 參考
description: 代表 GeometryShape 的幾何路徑
type: docs
url: /zh-hant/com.aspose.slides/geometrypath/
---
**繼承:**  
java.lang.Object

**全部已實作的介面:**  
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)  
```
public final class GeometryPath implements IGeometryPath
```

表示 GeometryShape 的幾何路徑  
## 建構函式

| 建構函式 | 描述 |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | 建立 GeometryPath 的實例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPathData()](#getPathData--) | 傳回 GeometryShape 的幾何路徑，作為路徑段的陣列。 |
| [removeAt(int index)](#removeAt-int-) | 在幾何路徑的指定索引處移除段。 |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | 在路徑末端加入直線 |
| [lineTo(float x, float y)](#lineTo-float-float-) | 在路徑末端加入直線 |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | 在路徑的指定位置加入直線 |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | 在路徑的指定位置加入直線 |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | 在路徑末端加入三次貝茲曲線 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | 在路徑末端加入三次貝茲曲線 |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | 在路徑的指定位置加入三次貝茲曲線 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | 在路徑的指定位置加入三次貝茲曲線 |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | 在路徑末端加入二次貝茲曲線 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | 在路徑末端加入二次貝茲曲線 |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | 在路徑的指定位置加入二次貝茲曲線 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | 在路徑的指定位置加入二次貝茲曲線 |
| [closeFigure()](#closeFigure--) | 關閉此路徑的目前圖形 |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | 設定下一個點的位置。 |
| [moveTo(float x, float y)](#moveTo-float-float-) | 設定下一個點的位置。 |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | 將指定的弧線附加到路徑。 |
| [getFillMode()](#getFillMode--) | 設定填充模式 |
| [setFillMode(byte value)](#setFillMode-byte-) | 設定填充模式 |
| [getStroke()](#getStroke--) | 設定筆劃外觀 |
| [setStroke(boolean value)](#setStroke-boolean-) | 設定筆劃外觀 |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

建立 GeometryPath 的實例

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

傳回 GeometryShape 的幾何路徑，作為路徑段的陣列。

**傳回:**  
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

在幾何路徑的指定索引處移除段。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 應刪除之幾何路徑的索引。 |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

在路徑末端加入直線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 線段的終點 |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

在路徑末端加入直線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | float | 線段終點的 X 座標 |
| y | float | 線段終點的 Y 座標 |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

在路徑的指定位置加入直線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 終點 |
| index | long | PathData 中段的索引 |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

在路徑的指定位置加入直線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | float | 點的 X 座標 |
| y | float | 點的 Y 座標 |
| index | long | PathData 中段的索引 |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

在路徑末端加入三次貝茲曲線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 第一個方向點 |
| point2 | java.awt.geom.Point2D.Float | 第二個方向點 |
| point3 | java.awt.geom.Point2D.Float | 終點 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

在路徑末端加入三次貝茲曲線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x1 | float | 第一個方向點的 X 座標 |
| y1 | float | 第一個方向點的 Y 座標 |
| x2 | float | 第二個方向點的 X 座標 |
| y2 | float | 第二個方向點的 Y 座標 |
| x3 | float | 終點的 X 座標 |
| y3 | float | 終點的 Y 座標 |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

在路徑的指定位置加入三次貝茲曲線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 第一個方向點 |
| point2 | java.awt.geom.Point2D.Float | 第二個方向點 |
| point3 | java.awt.geom.Point2D.Float | 終點 |
| index | long | PathData 中段的索引 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

在路徑的指定位置加入三次貝茲曲線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x1 | float | 第一個方向點的 X 座標 |
| y1 | float | 第一個方向點的 Y 座標 |
| x2 | float | 第二個方向點的 X 座標 |
| y2 | float | 第二個方向點的 Y 座標 |
| x3 | float | 終點的 X 座標 |
| y3 | float | 終點的 Y 座標 |
| index | long | PathData 中段的索引 |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

在路徑末端加入二次貝茲曲線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 方向點 |
| point2 | java.awt.geom.Point2D.Float | 終點 |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

在路徑末端加入二次貝茲曲線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x1 | float | 方向點的 X 座標 |
| y1 | float | 方向點的 Y 座標 |
| x2 | float | 終點的 X 座標 |
| y2 | float | 終點的 Y 座標 |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

在路徑的指定位置加入二次貝茲曲線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 方向點 |
| point2 | java.awt.geom.Point2D.Float | 終點 |
| index | long | PathData 中段的索引 |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

在路徑的指定位置加入二次貝茲曲線

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x1 | float | 方向點的 X 座標 |
| y1 | float | 方向點的 Y 座標 |
| x2 | float | 終點的 X 座標 |
| y2 | float | 終點的 Y 座標 |
| index | long | PathData 中段的索引 |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

關閉此路徑的當前圖形

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

設定下一個點的位置。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 點的位置 |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

設定下一個點的位置。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | float | 點的 X 座標 |
| y | float | 點的 Y 座標 |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

將指定的弧線附加到路徑。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| width | float | 矩形的寬度 |
| heigth | float | 矩形的高度 |
| startAngle | float | 起始角度。 |
| sweepAngle | float | 掃描角度 |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

設定填充模式

**傳回:**  
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

設定填充模式

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

設定筆劃外觀

**傳回:**  
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

設定筆劃外觀

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |