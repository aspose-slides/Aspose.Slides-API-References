---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: 表示 GeometryShape 的几何路径
type: docs
url: /zh/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

表示 GeometryShape 的几何路径
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPathData()](#getPathData--) | 返回 GeometryShape 的几何路径，作为路径段的数组。 |
| [removeAt(int index)](#removeAt-int-) | 删除几何路径中指定索引处的段。 |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | 在路径末尾添加直线 |
| [lineTo(float x, float y)](#lineTo-float-float-) | 在路径末尾添加直线 |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | 在路径的指定位置添加直线 |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | 在路径的指定位置添加直线 |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | 在路径末尾添加三次贝塞尔曲线 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | 在路径末尾添加三次贝塞尔曲线 |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | 在路径的指定位置添加三次贝塞尔曲线 |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | 在路径的指定位置添加三次贝塞尔曲线 |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | 在路径末尾添加二次贝塞尔曲线 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | 在路径末尾添加二次贝塞尔曲线 |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | 在路径的指定位置添加二次贝塞尔曲线 |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | 在路径的指定位置添加二次贝塞尔曲线 |
| [closeFigure()](#closeFigure--) | 闭合此路径的当前图形 |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | 设置下一个点的位置。 |
| [moveTo(float x, float y)](#moveTo-float-float-) | 设置下一个点的位置。 |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | 向路径追加指定的弧。 |
| [getFillMode()](#getFillMode--) | 设置填充模式 |
| [setFillMode(byte value)](#setFillMode-byte-) | 设置填充模式 |
| [getStroke()](#getStroke--) | 设置描边外观 |
| [setStroke(boolean value)](#setStroke-boolean-) | 设置描边外观 |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

返回 GeometryShape 的几何路径，作为路径段的数组。

**返回值:**  
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

删除几何路径中指定索引处的段。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的几何路径的索引。 |
### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```

在路径末尾添加直线

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 线段的终点 |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

在路径末尾添加直线

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 线段终点的 X 坐标 |
| y | float | 线段终点的 Y 坐标 |
### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```

在路径的指定位置添加直线

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 终点 |
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
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

在路径末尾添加三次贝塞尔曲线

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 第一个方向点 |
| point2 | java.awt.geom.Point2D.Float | 第二个方向点 |
| point3 | java.awt.geom.Point2D.Float | 终点 |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

在路径末尾添加三次贝塞尔曲线

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 第一个方向点的 X 坐标 |
| y1 | float | 第一个方向点的 Y 坐标 |
| x2 | float | 第二个方向点的 X 坐标 |
| y2 | float | 第二个方向点的 Y 坐标 |
| x3 | float | 终点的 X 坐标 |
| y3 | float | 终点的 Y 坐标 |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

在路径的指定位置添加三次贝塞尔曲线

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 第一个方向点 |
| point2 | java.awt.geom.Point2D.Float | 第二个方向点 |
| point3 | java.awt.geom.Point2D.Float | 终点 |
| index | long | PathData 中段的索引 |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

在路径的指定位置添加三次贝塞尔曲线

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 第一个方向点的 X 坐标 |
| y1 | float | 第一个方向点的 Y 坐标 |
| x2 | float | 第二个方向点的 X 坐标 |
| y2 | float | 第二个方向点的 Y 坐标 |
| x3 | float | 终点的 X 坐标 |
| y3 | float | 终点的 Y 坐标 |
| index | long | PathData 中段的索引 |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

在路径末尾添加二次贝塞尔曲线

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 方向点 |
| point2 | java.awt.geom.Point2D.Float | 终点 |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

在路径末尾添加二次贝塞尔曲线

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 方向点的 X 坐标 |
| y1 | float | 方向点的 Y 坐标 |
| x2 | float | 终点的 X 坐标 |
| y2 | float | 终点的 Y 坐标 |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

在路径的指定位置添加二次贝塞尔曲线

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | 方向点 |
| point2 | java.awt.geom.Point2D.Float | 终点 |
| index | long | PathData 中段的索引 |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

在路径的指定位置添加二次贝塞尔曲线

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | float | 方向点的 X 坐标 |
| y1 | float | 方向点的 Y 坐标 |
| x2 | float | 终点的 X 坐标 |
| y2 | float | 终点的 Y 坐标 |
| index | long | PathData 中段的索引 |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

闭合此路径的当前图形
### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```

设置下一个点的位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | 点的位置 |
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

向路径追加指定的弧。

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

**返回值:**
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

设置描边外观

**返回值:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

设置描边外观

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |