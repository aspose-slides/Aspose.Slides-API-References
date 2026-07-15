---
title: GeometryPath
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示 GeometryShape 的幾何路徑
type: docs
url: /zh-hant/com.aspose.slides/geometrypath/
---
**繼承:**  
java.lang.Object

**已實作的介面:**  
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)  
```
public final class GeometryPath implements IGeometryPath
```

表示 GeometryShape 的幾何路徑
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | 建立 GeometryPath 的實例 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPathData()](#getPathData--) | 傳回 GeometryShape 的幾何路徑，作為路徑段的陣列。 |
| [removeAt(int index)](#removeAt-int-) | 移除幾何路徑中指定索引處的段。 |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | 在路徑的結尾新增直線 |
| [lineTo(float x, float y)](#lineTo-float-float-) | 在路徑的結尾新增直線 |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | 在路徑的指定位置新增直線 |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | 在路徑的指定位置新增直線 |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | 在路徑的結尾新增三次 Bezier 曲線 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | 在路徑的結尾新增三次 Bezier 曲線 |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | 在路徑的指定位置新增三次 Bezier 曲線 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | 在路徑的指定位置新增三次 Bezier 曲線 |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | 在路徑的結尾新增二次 Bezier 曲線 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | 在路徑的結尾新增二次 Bezier 曲線 |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | 在路徑的指定位置新增二次 Bezier 曲線 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | 在路徑的指定位置新增二次 Bezier 曲線 |
| [closeFigure()](#closeFigure--) | 關閉此路徑當前的圖形 |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | 設定下一個點的位置。 |
| [moveTo(float x, float y)](#moveTo-float-float-) | 設定下一個點的位置。 |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | 將指定的弧線附加到路徑。 |
| [getFillMode()](#getFillMode--) | 設定填充模式 |
| [setFillMode(byte value)](#setFillMode-byte-) | 設定填充模式 |
| [getStroke()](#getStroke--) | 設定筆畫外觀 |
| [setStroke(boolean value)](#setStroke-boolean-) | 設定筆畫外觀 |
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

移除幾何路徑中指定索引處的段。

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| index | int | 要刪除的幾何路徑索引。 |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

在路徑的結尾新增直線

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| point | android.graphics.PointF | 直線的終點 |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

在路徑的結尾新增直線

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| x | float | 直線終點的 X 座標 |
| y | float | 直線終點的 Y 座標 |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

在路徑的指定位置新增直線

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| point | android.graphics.PointF | 終點 |
| index | long | PathData 中段的索引 |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

在路徑的指定位置新增直線

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| x | float | 點的 X 座標 |
| y | float | 點的 Y 座標 |
| index | long | PathData 中段的索引 |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

在路徑的結尾新增三次 Bezier 曲線

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 第一個方向點 |
| point2 | android.graphics.PointF | 第二個方向點 |
| point3 | android.graphics.PointF | 終點 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

在路徑的結尾新增三次 Bezier 曲線

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| x1 | float | 第一個方向點的 X 座標 |
| y1 | float | 第一個方向點的 Y 座標 |
| x2 | float | 第二個方向點的 X 座標 |
| y2 | float | 第二個方向點的 Y 座標 |
| x3 | float | 終點的 X 座標 |
| y3 | float | 終點的 Y 座標 |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

在路徑的指定位置新增三次 Bezier 曲線

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 第一個方向點 |
| point2 | android.graphics.PointF | 第二個方向點 |
| point3 | android.graphics.PointF | 終點 |
| index | long | PathData 中段的索引 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

在路徑的指定位置新增三次 Bezier 曲線

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| x1 | float | 第一個方向點的 X 座標 |
| y1 | float | 第一個方向點的 Y 座標 |
| x2 | float | 第二個方向點的 X 座標 |
| y2 | float | 第二個方向點的 Y 座標 |
| x3 | float | 終點的 X 座標 |
| y3 | float | 終點的 Y 座標 |
| index | long | PathData 中段的索引 |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

在路徑的結尾新增二次 Bezier 曲線

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 方向點 |
| point2 | android.graphics.PointF | 終點 |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

在路徑的結尾新增二次 Bezier 曲線

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| x1 | float | 方向點的 X 座標 |
| y1 | float | 方向點的 Y 座標 |
| x2 | float | 終點的 X 座標 |
| y2 | float | 終點的 Y 座標 |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

在路徑的指定位置新增二次 Bezier 曲線

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 方向點 |
| point2 | android.graphics.PointF | 終點 |
| index | long | PathData 中段的索引 |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

在路徑的指定位置新增二次 Bezier 曲線

**參數:**
| 參數 | Type | 說明 |
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

關閉此路徑當前的圖形

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

設定下一個點的位置。

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| point | android.graphics.PointF | 點的位置 |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

設定下一個點的位置。

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| x | float | 點的 X 座標 |
| y | float | 點的 Y 座標 |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

將指定的弧線附加到路徑。

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| width | float | 矩形的寬度 |
| heigth | float | 矩形的高度 |
| startAngle | float | 起始角度。 |
| sweepAngle | float | 掃過角度/ |

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
| 參數 | Type | 說明 |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

設定筆畫外觀

**傳回:**  
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

設定筆畫外觀

**參數:**
| 參數 | Type | 說明 |
| --- | --- | --- |
| value | boolean |  |