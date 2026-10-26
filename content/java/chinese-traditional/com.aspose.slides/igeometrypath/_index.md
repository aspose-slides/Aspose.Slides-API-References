---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /zh-hant/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

表示 GeometryShape 的幾何路徑
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPathData()](#getPathData--) | 以路徑段陣列形式傳回 GeometryShape 的幾何路徑。 |
| [removeAt(int index)](#removeAt-int-) | 移除幾何路徑中指定索引位置的段。 |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | 在路徑末端新增直線 |
| [lineTo(float x, float y)](#lineTo-float-float-) | 在路徑末端新增直線 |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | 在路徑指定位置新增直線 |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | 在路徑指定位置新增直線 |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | 在路徑末端新增立方貝塞爾曲線 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | 在路徑末端新增立方貝塞爾曲線 |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | 在路徑指定位置新增立方貝塞爾曲線 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | 在路徑指定位置新增立方貝塞爾曲線 |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | 在路徑末端新增二次貝塞爾曲線 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | 在路徑末端新增二次貝塞爾曲線 |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | 在路徑指定位置新增二次貝塞爾曲線 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | 在路徑指定位置新增二次貝塞爾曲線 |
| [closeFigure()](#closeFigure--) | 關閉此路徑的目前圖形 |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | 設定下一個點的位置。 |
| [moveTo(float x, float y)](#moveTo-float-float-) | 設定下一個點的位置。 |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | 將指定的弧線附加到路徑。 |
| [getFillMode()](#getFillMode--) | 設定填充模式 |
| [setFillMode(byte value)](#setFillMode-byte-) | 設定填充模式 |
| [getStroke()](#getStroke--) | 設定筆畫外觀 |
| [setStroke(boolean value)](#setStroke-boolean-) | 設定筆畫外觀 |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

回傳 geometry path of GeometryShape as an array of path segments.

**回傳：**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除幾何路徑中指定索引位置的段。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要刪除的幾何路徑段之索引。 |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```

在路徑末端新增直線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 直線的終點 |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

在路徑末端新增直線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 直線終點的 X 座標 |
| y | float | 直線終點的 Y 座標 |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```

在路徑指定位置新增直線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 終點 |
| index | long | PathData 中段的索引 |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

在路徑指定位置新增直線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 點的 X 座標 |
| y | float | 點的 Y 座標 |
| index | long | PathData 中段的索引 |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

在路徑末端新增立方貝塞爾曲線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 第一個方向點 |
| point2 | java.awt.geom.Point2D.Float | 第二個方向點 |
| point3 | java.awt.geom.Point2D.Float | 終點 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

在路徑末端新增立方貝塞爾曲線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x1 | float | 第一個方向點的 X 座標 |
| y1 | float | 第一個方向點的 Y 座標 |
| x2 | float | 第二個方向點的 X 座標 |
| y2 | float | 第二個方向點的 Y 座標 |
| x3 | float | 終點的 X 座標 |
| y3 | float | 終點的 Y 座標 |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

在路徑指定位置新增立方貝塞爾曲線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 第一個方向點 |
| point2 | java.awt.geom.Point2D.Float | 第二個方向點 |
| point3 | java.awt.geom.Point2D.Float | 終點 |
| index | long | PathData 中段的索引 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

在路徑指定位置新增立方貝塞爾曲線

**參數：**
| 參數 | 類型 | 說明 |
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
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

在路徑末端新增二次貝塞爾曲線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 方向點 |
| point2 | java.awt.geom.Point2D.Float | 終點 |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

在路徑末端新增二次貝塞爾曲線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x1 | float | 方向點的 X 座標 |
| y1 | float | 方向點的 Y 座標 |
| x2 | float | 終點的 X 座標 |
| y2 | float | 終點的 Y 座標 |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

在路徑指定位置新增二次貝塞爾曲線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 方向點 |
| point2 | java.awt.geom.Point2D.Float | 終點 |
| index | long | PathData 中段的索引 |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

在路徑指定位置新增二次貝塞爾曲線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x1 | float | 方向點的 X 座標 |
| y1 | float | 方向點的 Y 座標 |
| x2 | float | 終點的 X 座標 |
| y2 | float | 終點的 Y 座標 |
| index | long | PathData 中段的索引 |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

關閉此路徑的目前圖形

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```

設定下一個點的位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 點的位置 |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

設定下一個點的位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 點的 X 座標 |
| y | float | 點的 Y 座標 |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

將指定的弧線附加到路徑。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| width | float | 矩形的寬度 |
| heigth | float | 矩形的高度 |
| startAngle | float | 起始角度。 |
| sweepAngle | float | 掃過角度/ |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

設定填充模式

**回傳：**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

設定填充模式

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

設定筆畫外觀

**回傳：**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

設定筆畫外觀

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |