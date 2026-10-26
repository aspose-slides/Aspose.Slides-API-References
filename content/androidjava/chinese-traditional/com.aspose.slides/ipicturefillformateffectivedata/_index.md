---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 不可變的物件，包含圖片填充的屬性。
type: docs
url: /zh-hant/com.aspose.slides/ipicturefillformateffectivedata/
---
**所有已實作的介面：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

不可變的物件，包含圖片填充的屬性。

--------------------

此介面用作 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) 的一部分。
## 方法

| Method | Description |
| --- | --- |
| [getDpi()](#getDpi--) | 返回用於填充圖片的 dpi。 |
| [getPictureFillMode()](#getPictureFillMode--) | 返回圖片填充模式。 |
| [getPicture()](#getPicture--) | 返回圖片。 |
| [getCropLeft()](#getCropLeft--) | 返回實際圖像寬度的百分比，表示圖片左側被裁剪的部分。 |
| [getCropTop()](#getCropTop--) | 返回實際圖像高度的百分比，表示圖片頂部被裁剪的部分。 |
| [getCropRight()](#getCropRight--) | 返回實際圖像寬度的百分比，表示圖片右側被裁剪的部分。 |
| [getCropBottom()](#getCropBottom--) | 返回實際圖像高度的百分比，表示圖片底部被裁剪的部分。 |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


返回用於填充圖片的 dpi。唯讀 int。

**傳回值：**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


返回圖片填充模式。唯讀 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**傳回值：**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


返回圖片。唯讀 [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)。

**傳回值：**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


返回實際圖像寬度的百分比，表示圖片左側被裁剪的部分。唯讀 float。

**傳回值：**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


返回實際圖像高度的百分比，表示圖片頂部被裁剪的部分。唯讀 float。

**傳回值：**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


返回實際圖像寬度的百分比，表示圖片右側被裁剪的部分。唯讀 float。

**傳回值：**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


返回實際圖像高度的百分比，表示圖片底部被裁剪的部分。唯讀 float。

**傳回值：**
float