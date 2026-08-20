---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 不可變的物件，包含圖片填充的屬性。
type: docs
url: /zh-hant/com.aspose.slides/ipicturefillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

不可變的物件，包含圖片填充的屬性。

--------------------

此介面作為 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) 的一部分使用。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDpi()](#getDpi--) | 返回用於填充圖片的 DPI。 |
| [getPictureFillMode()](#getPictureFillMode--) | 返回圖片填充模式。 |
| [getPicture()](#getPicture--) | 返回圖片。 |
| [getCropLeft()](#getCropLeft--) | 返回從圖片左邊裁切的實際圖像寬度百分比。 |
| [getCropTop()](#getCropTop--) | 返回從圖片頂部裁切的實際圖像高度百分比。 |
| [getCropRight()](#getCropRight--) | 返回從圖片右邊裁切的實際圖像寬度百分比。 |
| [getCropBottom()](#getCropBottom--) | 返回從圖片底部裁切的實際圖像高度百分比。 |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

返回用於填充圖片的 DPI。唯讀 int。

**回傳:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

返回圖片填充模式。唯讀 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**回傳:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

返回圖片。唯讀 [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)。

**回傳:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

返回從圖片左邊裁切的實際圖像寬度百分比。唯讀 float。

**回傳:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

返回從圖片頂部裁切的實際圖像高度百分比。唯讀 float。

**回傳:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

返回從圖片右邊裁切的實際圖像寬度百分比。唯讀 float。

**回傳:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

返回從圖片底部裁切的實際圖像高度百分比。唯讀 float。

**回傳:**
float