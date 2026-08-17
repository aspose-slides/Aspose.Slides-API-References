---
title: IColorChange
second_title: Aspose.Slides Java API 参考
description: 表示一种颜色变换效果。
type: docs
url: /zh/com.aspose.slides/icolorchange/
---
**所有实现的接口:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

表示一种颜色变换效果。FromColor 的实例将被 ToColor 的实例替换。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 将被替换的颜色。 |
| [getToColor()](#getToColor--) | 用于替换的颜色。 |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


将被替换的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


用于替换的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)