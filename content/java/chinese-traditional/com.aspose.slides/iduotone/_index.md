---
title: IDuotone
second_title: Aspose.Slides for Java API 參考
description: 表示雙調效果。
type: docs
url: /zh-hant/com.aspose.slides/iduotone/
---
**所有已實作的介面：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IDuotone extends IImageTransformOperation, IAccessiblePVIObject<IDuotoneEffectiveData>
```

表示雙調效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor1()](#getColor1--) | 返回暗像素的目標色彩格式。 |
| [getColor2()](#getColor2--) | 返回亮像素的目標色彩格式。 |
### getColor1() {#getColor1--}
```
public abstract IColorFormat getColor1()
```

返回暗像素的目標色彩格式。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public abstract IColorFormat getColor2()
```

返回亮像素的目標色彩格式。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)