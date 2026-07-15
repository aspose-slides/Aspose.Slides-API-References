---
title: IColorChange
second_title: Aspose.Slides for Android via Java API 參考
description: 代表顏色變更效果。
type: docs
url: /zh-hant/com.aspose.slides/icolorchange/
---
**已實作的介面：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

代表一個顏色變更效果。FromColor 的實例將被 ToColor 的實例取代。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 將被取代的 Color。 |
| [getToColor()](#getToColor--) | 用於取代的 Color。 |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


將被取代的 Color。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


用於取代的 Color。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)