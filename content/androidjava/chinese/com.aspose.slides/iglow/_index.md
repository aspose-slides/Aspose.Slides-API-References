---
title: IGlow
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一种辉光效果，在该效果中，颜色模糊的轮廓被添加在对象的边缘之外。
type: docs
url: /zh/com.aspose.slides/iglow/
---
**已实现的接口：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

表示一种辉光效果，在该效果中，颜色模糊的轮廓会添加在对象边缘之外。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 半径。 |
| [setRadius(double value)](#setRadius-double-) | 半径。 |
| [getColor()](#getColor--) | 颜色格式。 |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

半径。可读写 double.

**返回值：**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

半径。可读写 double.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

颜色格式。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)