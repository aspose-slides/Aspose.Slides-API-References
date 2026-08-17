---
title: ShapeElement
second_title: Aspose.Slides for Java API 参考
description: 表示具有相同轮廓和填充属性的形状的一部分。
type: docs
url: /zh/com.aspose.slides/shapeelement/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

表示具有相同轮廓和填充属性的形状的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getParentShape()](#getParentShape--) | 返回创建该元素的 Shape_PPT。 |
| [getPathPoints()](#getPathPoints--) | 获取定义元素路径几何形状的点数组。 |
| [getPathTypes()](#getPathTypes--) | 获取指定元素路径中每个点类型的字节值数组。 |
| [getFillSource()](#getFillSource--) | 返回有关如何填充元素的信息。 |
| [getStrokeSource()](#getStrokeSource--) | 返回有关如何描边元素的信息。 |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


返回创建该元素的 Shape_PPT。只读 [Shape](../../com.aspose.slides/shape)。

**返回：**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```


获取定义元素路径几何形状的点数组。

**返回：**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


获取指定元素路径中每个点类型的字节值数组。

**0** 表示该点是图形的起始点。

**1** 表示该点是线段的两个端点之一。

**3** 表示该点是三次贝塞尔样条的端点或控制点。

**7** 将除最低三位之外的所有位掩码清零，这三位指示点的类型。

**16** 指定相应的段为虚线。

**32** 指定该点为标记。

**128** 指定该点是闭合子路径（图形）中的最后一点。

**129** 表示既是线段端点又是闭合子路径的最后一点的数据点。

**返回：**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


返回有关如何填充元素的信息。只读 [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource)。

**返回：**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


返回有关如何描边元素的信息。只读 [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource)。

**返回：**
byte