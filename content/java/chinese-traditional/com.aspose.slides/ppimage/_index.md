---
title: PPImage
second_title: Aspose.Slides for Java API 參考
description: 代表投影片中的圖像。
type: docs
url: /zh-hant/com.aspose.slides/ppimage/
---
**繼承:**
java.lang.Object

**所有實作的介面:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

代表投影片中的圖像。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | 傳回圖像資料的副本。 |
| [getImage()](#getImage--) | 傳回圖像的副本。 |
| [getSvgImage()](#getSvgImage--) | 傳回或設定 ISvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | 傳回或設定 ISvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | 取代圖像資料。 |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | 取代圖像資料。 |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | 取代圖像資料。 |
| [getContentType()](#getContentType--) | 傳回圖像的 MIME 類型，已編碼於 BinaryData (\#getBinaryData.getBinaryData)。 |
| [getWidth()](#getWidth--) | 傳回圖像的寬度。 |
| [getHeight()](#getHeight--) | 傳回圖像的高度。 |
| [getX()](#getX--) | 傳回圖像的 X 偏移。 |
| [getY()](#getY--) | 傳回圖像的 Y 偏移。 |
| [hashCode()](#hashCode--) | 傳回圖像的雜湊碼。 |
| [dispose()](#dispose--) | 釋放物件。 |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


傳回圖像資料的副本。唯讀 byte[] 。

**傳回:**
byte[] - 位元組陣列
### getImage() {#getImage--}
```
public final IImage getImage()
```


傳回圖像的副本。唯讀 [IImage](../../com.aspose.slides/iimage)。

**傳回:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


傳回或設定 ISvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

此值表示此圖像是從 SVG 建立的。

**傳回:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


傳回或設定 ISvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

此值表示此圖像是從 SVG 建立的。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


取代圖像資料。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| newImageData | byte[] | 新圖像的資料。 |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


取代圖像資料。注意：當 Image 為中繪圖檔案時，將被光栅化。請改用 ReplaceImage(byte[])。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | 新的圖像。 |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


取代圖像資料。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | 新的 IPPImage。 |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


傳回圖像的 MIME 類型，已編碼於 BinaryData (\#getBinaryData.getBinaryData)。唯讀 String。

**傳回:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


傳回圖像的寬度。唯讀 int 。

**傳回:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


傳回圖像的高度。唯讀 int 。

**傳回:**
int
### getX() {#getX--}
```
public final int getX()
```


傳回圖像的 X 偏移。唯讀 int 。

**傳回:**
int
### getY() {#getY--}
```
public final int getY()
```


傳回圖像的 Y 偏移。唯讀 int 。

**傳回:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


傳回圖像的雜湊碼。

**傳回:**
int - 雜湊碼。
### dispose() {#dispose--}
```
public final void dispose()
```


釋放物件。