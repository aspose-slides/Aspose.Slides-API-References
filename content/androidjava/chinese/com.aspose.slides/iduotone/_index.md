---
title: IDuotone
second_title: Aspose.Slides for Android(通过 Java API 参考)
description: 表示双色调效果。
type: docs
url: /zh/com.aspose.slides/iduotone/
---
**所有实现的接口：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IDuotone extends IImageTransformOperation, IAccessiblePVIObject<IDuotoneEffectiveData>
```

表示双色调效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor1()](#getColor1--) | 返回暗像素的目标颜色格式。 |
| [getColor2()](#getColor2--) | 返回亮像素的目标颜色格式。 |
### getColor1() {#getColor1--}
```
public abstract IColorFormat getColor1()
```

返回暗像素的目标颜色格式。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public abstract IColorFormat getColor2()
```

返回亮像素的目标颜色格式。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)