---
title: PPImage
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một hình ảnh trong bản trình bày.
type: docs
url: /vi/com.aspose.slides/ppimage/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Đại diện cho một hình ảnh trong bản trình bày.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Trả về bản sao dữ liệu của hình ảnh. |
| [getImage()](#getImage--) | Trả về bản sao của hình ảnh. |
| [getSvgImage()](#getSvgImage--) | Trả về hoặc đặt đối tượng ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Trả về hoặc đặt đối tượng ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Thay thế dữ liệu hình ảnh. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Thay thế dữ liệu hình ảnh. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Thay thế dữ liệu hình ảnh. |
| [getContentType()](#getContentType--) | Trả về kiểu MIME của hình ảnh, được mã hoá trong BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Trả về độ rộng của hình ảnh. |
| [getHeight()](#getHeight--) | Trả về chiều cao của hình ảnh. |
| [getX()](#getX--) | Trả về độ dịch X của hình ảnh. |
| [getY()](#getY--) | Trả về độ dịch Y của hình ảnh. |
| [hashCode()](#hashCode--) | Trả về mã băm của hình ảnh. |
| [dispose()](#dispose--) | Giải phóng đối tượng. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Trả về bản sao dữ liệu của hình ảnh. Chỉ đọc byte[] .

**Trả về:**
byte[] - Mảng byte
### getImage() {#getImage--}
```
public final IImage getImage()
```

Trả về bản sao của hình ảnh. Chỉ đọc [IImage](../../com.aspose.slides/iimage).

**Trả về:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

Trả về hoặc đặt đối tượng ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Giá trị này cho biết rằng hình ảnh này được tạo từ SVG.

**Trả về:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

Trả về hoặc đặt đối tượng ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Giá trị này cho biết rằng hình ảnh này được tạo từ SVG.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```

Thay thế dữ liệu hình ảnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| newImageData | byte[] | Dữ liệu của hình ảnh mới. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

Thay thế dữ liệu hình ảnh. Lưu ý: khi Image là metafile - nó sẽ được raster hoá. Sử dụng ReplaceImage(byte[]) thay thế

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Hình ảnh mới. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

Thay thế dữ liệu hình ảnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage mới. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Trả về kiểu MIME của hình ảnh, được mã hoá trong BinaryData (\#getBinaryData.getBinaryData). Chỉ đọc String.

**Trả về:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```

Trả về độ rộng của hình ảnh. Chỉ đọc int .

**Trả về:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```

Trả về chiều cao của hình ảnh. Chỉ đọc int .

**Trả về:**
int
### getX() {#getX--}
```
public final int getX()
```

Trả về độ dịch X của hình ảnh. Chỉ đọc int .

**Trả về:**
int
### getY() {#getY--}
```
public final int getY()
```

Trả về độ dịch Y của hình ảnh. Chỉ đọc int .

**Trả về:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```

Trả về mã băm của hình ảnh.

**Trả về:**
int - Mã băm.
### dispose() {#dispose--}
```
public final void dispose()
```

Giải phóng đối tượng.