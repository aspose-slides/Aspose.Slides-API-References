---
title: IGlow
second_title: Aspose.Slides for Java API 参考
description: 表示一种 Glow 效果，其中在对象边缘之外添加颜色模糊轮廓。
type: docs
url: /zh/com.aspose.slides/iglow/
---
**所有实现的接口：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

表示一种 Glow 效果，其中在对象边缘之外添加颜色模糊轮廓。
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


半径。读/写 double.

**返回:**
double

### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


半径。读/写 double.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


颜色格式。只读 [IColorFormat](../../com.aspose.slides/icolorformat).

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)