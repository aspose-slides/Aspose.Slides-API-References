---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: 表示演示文稿中的图像。
type: docs
url: /zh/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

表示演示文稿中的图像。
## 方法

| Method | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | 返回图像数据的副本。 |
| [getImage()](#getImage--) | 返回图像的副本。 |
| [getSvgImage()](#getSvgImage--) | 返回或设置 ISvgImage 对象 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | 返回或设置 ISvgImage 对象 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | 替换图像数据。 |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | 替换图像。 |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | 替换图像。 |
| [getContentType()](#getContentType--) | 返回图像的 MIME 类型，已在 \#getBinaryData.getBinaryData 中编码。 |
| [getWidth()](#getWidth--) | 返回图像的宽度。 |
| [getHeight()](#getHeight--) | 返回图像的高度。 |
| [getX()](#getX--) | 返回图像的 X 偏移量。 |
| [getY()](#getY--) | 返回图像的 Y 偏移量。 |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

返回图像数据的副本。只读 byte[]。

**返回：**
byte[]

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

返回图像的副本。只读 \#getImage.getImage。

**返回：**
[IImage](../../com.aspose.slides/iimage)

### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

返回或设置 ISvgImage 对象 [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

此值表示此图像是从 SVG 创建的。

**返回：**
[ISvgImage](../../com.aspose.slides/isvgimage)

### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

返回或设置 ISvgImage 对象 [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

此值表示此图像是从 SVG 创建的。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

替换图像数据。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | 新图像的数据。 |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

替换图像。注意：当 Image 为元文件时，它将被光栅化。请改用 replaceImage(byte[])。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | 新图像。 |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

替换图像。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | 新的 IPPImage。 |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

返回图像的 MIME 类型，已在 \#getBinaryData.getBinaryData 中编码。只读 String。

**返回：**
java.lang.String

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

返回图像的宽度。只读 int。

**返回：**
int

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

返回图像的高度。只读 int。

**返回：**
int

### getX() {#getX--}
```
public abstract int getX()
```

返回图像的 X 偏移量。只读 int。

**返回：**
int

### getY() {#getY--}
```
public abstract int getY()
```

返回图像的 Y 偏移量。只读 int。

**返回：**
int