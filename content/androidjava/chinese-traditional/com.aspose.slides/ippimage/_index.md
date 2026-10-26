---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an image in a presentation.
type: docs
url: /zh-hant/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

表示簡報中的圖像。
## 方法

| Method | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | 傳回圖像資料的副本。 |
| [getImage()](#getImage--) | 傳回圖像的副本。 |
| [getSvgImage()](#getSvgImage--) | 傳回或設定 ISvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | 傳回或設定 ISvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | 取代圖像資料。 |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | 取代圖像。 |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | 取代圖像。 |
| [getContentType()](#getContentType--) | 傳回圖像的 MIME 類型，編碼於 \#getBinaryData.getBinaryData。 |
| [getWidth()](#getWidth--) | 傳回圖像的寬度。 |
| [getHeight()](#getHeight--) | 傳回圖像的高度。 |
| [getX()](#getX--) | 傳回圖像的 X 偏移量。 |
| [getY()](#getY--) | 傳回圖像的 Y 偏移量。 |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

傳回圖像資料的副本。唯讀 byte[]。

**傳回：**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

傳回圖像的副本。唯讀 \#getImage.getImage。

**傳回：**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

傳回或設定 ISvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage)

此值表示此圖像是從 SVG 建立的。

**傳回：**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

傳回或設定 ISvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage)

此值表示此圖像是從 SVG 建立的。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

取代圖像資料。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | 新圖像的資料。 |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

取代圖像。注意：當圖像是中繼檔案時，將會被光柵化。請改用 replaceImage(byte[])。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | 新圖像。 |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

取代圖像。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | 新 IPPImage。 |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

傳回圖像的 MIME 類型，編碼於 \#getBinaryData.getBinaryData。唯讀 String。

**傳回：**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

傳回圖像的寬度。唯讀 int。

**傳回：**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

傳回圖像的高度。唯讀 int。

**傳回：**
int
### getX() {#getX--}
```
public abstract int getX()
```

傳回圖像的 X 偏移量。唯讀 int。

**傳回：**
int
### getY() {#getY--}
```
public abstract int getY()
```

傳回圖像的 Y 偏移量。唯讀 int。

**傳回：**
int