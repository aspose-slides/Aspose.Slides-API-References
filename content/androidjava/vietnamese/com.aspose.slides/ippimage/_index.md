---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn một hình ảnh trong bài thuyết trình.
type: docs
url: /vi/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Biểu diễn một hình ảnh trong bài thuyết trình.
## Phương thức

| Method | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Trả về bản sao dữ liệu của hình ảnh. |
| [getImage()](#getImage--) | Trả về bản sao của hình ảnh. |
| [getSvgImage()](#getSvgImage--) | Trả về hoặc đặt đối tượng ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Trả về hoặc đặt đối tượng ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Thay thế dữ liệu hình ảnh. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Thay thế hình ảnh. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Thay thế hình ảnh. |
| [getContentType()](#getContentType--) | Trả về kiểu MIME của một hình ảnh, được mã hoá trong \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Trả về chiều rộng của hình ảnh. |
| [getHeight()](#getHeight--) | Trả về chiều cao của hình ảnh. |
| [getX()](#getX--) | Trả về độ dịch X của hình ảnh. |
| [getY()](#getY--) | Trả về độ dịch Y của hình ảnh. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Trả về bản sao dữ liệu của hình ảnh. Chỉ đọc byte[].

**Trả về:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Trả về bản sao của hình ảnh. Chỉ đọc #getImage.getImage.

**Trả về:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

Trả về hoặc đặt đối tượng ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Giá trị này cho biết hình ảnh này được tạo từ SVG.

**Trả về:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

Trả về hoặc đặt đối tượng ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Giá trị này cho biết hình ảnh này được tạo từ SVG.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

Thay thế dữ liệu hình ảnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| newImageData | byte[] | Dữ liệu của hình ảnh mới. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

Thay thế hình ảnh. Lưu ý: khi Image là metafile - nó sẽ được raster hoá. Sử dụng replaceImage(byte[]) thay thế

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Hình ảnh mới. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

Thay thế hình ảnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage mới. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Trả về kiểu MIME của một hình ảnh, được mã hoá trong \#getBinaryData.getBinaryData. Chỉ đọc String.

**Trả về:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Trả về chiều rộng của hình ảnh. Chỉ đọc int.

**Trả về:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Trả về chiều cao của hình ảnh. Chỉ đọc int.

**Trả về:**
int
### getX() {#getX--}
```
public abstract int getX()
```

Trả về độ dịch X của hình ảnh. Chỉ đọc int.

**Trả về:**
int
### getY() {#getY--}
```
public abstract int getY()
```

Trả về độ dịch Y của hình ảnh. Chỉ đọc int.

**Trả về:**
int