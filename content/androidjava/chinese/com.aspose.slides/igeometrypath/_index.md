---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: 表示 GeometryShape 的几何路径
type: docs
url: /zh/com.aspose.slides/igeometrypath/
---```java
public interface IGeometryPath
```

表示 GeometryShape 的几何路径
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPathData()](#getPathData--) | 返回 GeometryShape 的几何路径，作为路径段的数组。 |
| [removeAt(int index)](#removeAt-int-) | 删除几何路径中指定索引的段。 |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | 在路径的末尾添加直线 |
| [lineTo(float x, float y)](#lineTo-float-float-) | 在路径的末尾添加直线 |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | 在路径的指定位置添加直线 |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | 在路径的指定位置添加直线 |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | 在路径的末尾添加三次 Bézier 曲线 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | 在路径的末尾添加三次 Bézier 曲线 |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | 在路径的指定位置添加三次 Bézier 曲线 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | 在路径的指定位置添加三次 Bézier 曲线 |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | 在路径的末尾添加二次 Bézier 曲线 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | 在路径的末尾添加二次 Bézier 曲线 |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | 在路径的指定位置添加二次 Bézier 曲线 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | 在路径的指定位置添加二次 Bézier 曲线 |
| [closeFigure()](#closeFigure--) | 关闭此路径的当前图形 |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | 设置下一个点的位置。 |
| [moveTo(float x, float y)](#moveTo-float-float-) | 设置下一个点的位置。 |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | 将指定的弧线追加到路径。 |
| [getFillMode()](#getFillMode--) | 设置填充模式 |
| [setFillMode(byte value)](#setFillMode-byte-) | 设置填充模式 |
| [getStroke()](#getStroke--) | 设置笔画外观 |
| [setStroke(boolean value)](#setStroke-boolean-) | 设置笔画外观 |

### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

返回 GeometryShape 的几何路径，作为路径段的数组。

**返回:**  
com.aspose.slides.IPathSegment[]

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

删除几何路径中指定索引的段。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应该删除的几何路径段的索引。 |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```

在路径的末尾添加直线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | android.graphics.PointF | 直线的结束点 |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

在路径的末尾添加直线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 直线结束点的 X 坐标 |
| y | float | 直线结束点的 Y 坐标 |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```

在路径的指定位置添加直线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | android.graphics.PointF | 结束点 |
| index | long | PathData 中段的索引 |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

在路径的指定位置添加直线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 点的 X 坐标 |
| y | float | 点的 Y 坐标 |
| index | long | PathData 中段的索引 |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

在路径的末尾添加三次 Bézier 曲线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 第一个方向点 |
| point2 | android.graphics.PointF | 第二个方向点 |
| point3 | android.graphics.PointF | 结束点 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

在路径的末尾添加三次 Bézier 曲线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 第一个方向点的 X 坐标 |
| y1 | float | 第一个方向点的 Y 坐标 |
| x2 | float | 第二个方向点的 X 坐标 |
| y2 | float | 第二个方向点的 Y 坐标 |
| x3 | float | 结束点的 X 坐标 |
| y3 | float | 结束点的 Y 坐标 |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

在路径的指定位置添加三次 Bézier 曲线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 第一个方向点 |
| point2 | android.graphics.PointF | 第二个方向点 |
| point3 | android.graphics.PointF | 结束点 |
| index | long | PathData 中段的索引 |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

在路径的指定位置添加三次 Bézier 曲线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 第一个方向点的 X 坐标 |
| y1 | float | 第一个方向点的 Y 坐标 |
| x2 | float | 第二个方向点的 X 坐标 |
| y2 | float | 第二个方向点的 Y 坐标 |
| x3 | float | 结束点的 X 坐标 |
| y3 | float | 结束点的 Y 坐标 |
| index | long | PathData 中段的索引 |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```

在路径的末尾添加二次 Bézier 曲线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 方向点 |
| point2 | android.graphics.PointF | 结束点 |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

在路径的末尾添加二次 Bézier 曲线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 方向点的 X 坐标 |
| y1 | float | 方向点的 Y 坐标 |
| x2 | float | 结束点的 X 坐标 |
| y2 | float | 结束点的 Y 坐标 |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```

在路径的指定位置添加二次 Bézier 曲线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | android.graphics.PointF | 方向点 |
| point2 | android.graphics.PointF | 结束点 |
| index | long | PathData 中段的索引 |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

在路径的指定位置添加二次 Bézier 曲线

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 方向点的 X 坐标 |
| y1 | float | 方向点的 Y 坐标 |
| x2 | float | 结束点的 X 坐标 |
| y2 | float | 结束点的 Y 坐标 |
| index | long | PathData 中段的索引 |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

关闭此路径的当前图形

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```

设置下一个点的位置。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | android.graphics.PointF | 点的位置 |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

设置下一个点的位置。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 点的 X 坐标 |
| y | float | 点的 Y 坐标 |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

将指定的弧线追加到路径。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | float | 矩形的宽度 |
| heigth | float | 矩形的高度 |
| startAngle | float | 起始角度。 |
| sweepAngle | float | 扫描角度/ |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

设置填充模式

**返回:**  
byte

### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

设置填充模式

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

设置笔画外观

**返回:**  
boolean

### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

设置笔画外观

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |