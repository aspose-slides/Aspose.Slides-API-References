---
title: IColorChange
second_title: Aspose.Slides for Java API 參考
description: 表示一個顏色變更效果。
type: docs
url: /zh-hant/com.aspose.slides/icolorchange/
---
**所有已实现的接口:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

表示一個顏色變更效果。FromColor 的實例會被 ToColor 的實例取代。
## 方法

| Method | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | 將被取代的顏色。 |
| [getToColor()](#getToColor--) | 將取代的顏色。 |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```

將被取代的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```

將取代的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)