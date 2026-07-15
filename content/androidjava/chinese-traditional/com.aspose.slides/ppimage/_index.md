---
title: PPImage
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示簡報中的圖像。
type: docs
url: /zh-hant/com.aspose.slides/ppimage/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

表示簡報中的圖像。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | 返回圖像資料的副本。 |
| [getImage()](#getImage--) | 返回圖像的副本。 |
| [getSvgImage()](#getSvgImage--) | 返回或設定 ISSvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | 返回或設定 ISSvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | 取代圖像資料。 |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | 取代圖像資料。 |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | 取代圖像資料。 |
| [getContentType()](#getContentType--) | 返回圖像的 MIME 類型，於 BinaryData 中編碼 (\#getBinaryData.getBinaryData)。 |
| [getWidth()](#getWidth--) | 返回圖像的寬度。 |
| [getHeight()](#getHeight--) | 返回圖像的高度。 |
| [getX()](#getX--) | 返回圖像的 X 偏移值。 |
| [getY()](#getY--) | 返回圖像的 Y 偏移值。 |
| [hashCode()](#hashCode--) | 返回圖像的雜湊碼。 |
| [dispose()](#dispose--) | 釋放物件。 |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

返回圖像資料的副本。唯讀 byte[] 。

**返回值：**
byte[] - 位元組陣列
### getImage() {#getImage--}
```
public final IImage getImage()
```

返回圖像的副本。唯讀 [IImage](../../com.aspose.slides/iimage)。

**返回值：**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

返回或設定 ISSvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

此值表示此圖像是由 SVG 建立的。

**返回值：**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

返回或設定 ISSvgImage 物件 [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

此值表示此圖像是由 SVG 建立的。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```

取代圖像資料。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newImageData | byte[] | 新圖像的資料。 |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

取代圖像資料。注意：當圖像是 metafile 時，將被光柵化。請改用 ReplaceImage(byte[])。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | 新圖像。 |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

取代圖像資料。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | 新的 IPPImage。 |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

返回圖像的 MIME 類型，於 BinaryData 中編碼 (\#getBinaryData.getBinaryData)。唯讀 String。

**返回值：**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```

返回圖像的寬度。唯讀 int 。

**返回值：**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```

返回圖像的高度。唯讀 int 。

**返回值：**
int
### getX() {#getX--}
```
public final int getX()
```

返回圖像的 X 偏移值。唯讀 int 。

**返回值：**
int
### getY() {#getY--}
```
public final int getY()
```

返回圖像的 Y 偏移值。唯讀 int 。

**返回值：**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```

返回圖像的雜湊碼。

**返回值：**
int - 雜湊碼。
### dispose() {#dispose--}
```
public final void dispose()
```

釋放物件。