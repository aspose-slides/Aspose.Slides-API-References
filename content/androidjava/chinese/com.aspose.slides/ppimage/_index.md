---
title: PPImage
second_title: Aspose.Slides for Android via Java API 参考
description: 表示演示文稿中的图像。
type: docs
url: /zh/com.aspose.slides/ppimage/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable  
```
public class PPImage implements IPPImage, System.IDisposable
```

表示演示文稿中的图像。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | 返回图像数据的副本。 |
| [getImage()](#getImage--) | 返回图像的副本。 |
| [getSvgImage()](#getSvgImage--) | 返回或设置 ISvgImage 对象 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | 返回或设置 ISvgImage 对象 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Replaces image data. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | 替换图像数据。 |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | 替换图像数据。 |
| [getContentType()](#getContentType--) | 返回图像的 MIME 类型，已在 BinaryData 中编码（\#getBinaryData.getBinaryData）。 |
| [getWidth()](#getWidth--) | 返回图像的宽度。 |
| [getHeight()](#getHeight--) | 返回图像的高度。 |
| [getX()](#getX--) | 返回图像的 X 偏移量。 |
| [getY()](#getY--) | 返回图像的 Y 偏移量。 |
| [hashCode()](#hashCode--) | 返回图像的哈希码。 |
| [dispose()](#dispose--) | 释放对象。 |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

返回图像数据的副本。只读  byte[] 。

**返回:**  
byte[] - 字节数组

### getImage() {#getImage--}
```
public final IImage getImage()
```

返回图像的副本。只读 [IImage](../../com.aspose.slides/iimage)。

**返回:**  
[IImage](../../com.aspose.slides/iimage)

### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

返回或设置 ISvgImage 对象 [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

此值指示该图像是由 SVG 创建的。

**返回:**  
[ISvgImage](../../com.aspose.slides/isvgimage)

### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

返回或设置 ISvgImage 对象 [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

此值指示该图像是由 SVG 创建的。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```

替换图像数据。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newImageData | byte[] | 新图像的数据。 |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

替换图像数据。注意：当 Image 为元文件时，它将被栅格化。请改用 ReplaceImage(byte[])。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | 新图像。 |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

替换图像数据。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | 新的 IPPImage。 |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

返回图像的 MIME 类型，已在 BinaryData 中编码（\#getBinaryData.getBinaryData）。只读 String。

**返回:**  
java.lang.String

### getWidth() {#getWidth--}
```
public final int getWidth()
```

返回图像的宽度。只读  int 。

**返回:**  
int

### getHeight() {#getHeight--}
```
public final int getHeight()
```

返回图像的高度。只读  int 。

**返回:**  
int

### getX() {#getX--}
```
public final int getX()
```

返回图像的 X 偏移量。只读  int 。

**返回:**  
int

### getY() {#getY--}
```
public final int getY()
```

返回图像的 Y 偏移量。只读  int 。

**返回:**  
int

### hashCode() {#hashCode--}
```
public int hashCode()
```

返回图像的哈希码。

**返回:**  
int - 哈希码。

### dispose() {#dispose--}
```
public final void dispose()
```

释放对象。