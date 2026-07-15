---
title: SvgImage
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một hình ảnh SVG.
type: docs
url: /vi/com.aspose.slides/svgimage/
---
**Kế thừa:**  
java.lang.Object

**Tất cả các Interface được triển khai:**  
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)  
```
public class SvgImage implements ISvgImage
```

Biểu diễn một hình ảnh SVG.

## Hàm khởi tạo

| Phương thức khởi tạo | Mô tả |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Tạo đối tượng SvgImage mới. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Tạo đối tượng SvgImage mới. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Tạo đối tượng SvgImage mới. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo đối tượng SvgImage mới. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo đối tượng SvgImage mới. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo đối tượng SvgImage mới. |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSvgData()](#getSvgData--) | Trả về dữ liệu SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Trả về giao diện callback dùng để giải quyết các tài nguyên bên ngoài khi nhập tài liệu Svg. |
| [getBaseUri()](#getBaseUri--) | Trả về URI cơ sở của Svg được chỉ định. |
| [getSvgContent()](#getSvgContent--) | Trả về nội dung SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Lưu hình ảnh SVG dưới dạng tệp EMF. |

### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Tạo đối tượng SvgImage mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| data | byte[] | Dữ liệu Svg. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Tạo đối tượng SvgImage mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| svgContent | java.lang.String | Nội dung Svg. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Tạo đối tượng SvgImage mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng Svg. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Tạo đối tượng SvgImage mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| data | byte[] | Dữ liệu Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| baseUri | java.lang.String | URI cơ sở của Svg được chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Tạo đối tượng SvgImage mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| svgContent | java.lang.String | Nội dung Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| baseUri | java.lang.String | URI cơ sở của Svg được chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Tạo đối tượng SvgImage mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| baseUri | java.lang.String | URI cơ sở của Svg được chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

Trả về dữ liệu SVG. Chỉ đọc byte[].

**Giá trị trả về:**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Trả về giao diện callback dùng để giải quyết các tài nguyên bên ngoài khi nhập tài liệu Svg. Chỉ đọc [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Giá trị trả về:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Trả về URI cơ sở của Svg được chỉ định. Được sử dụng để giải quyết các liên kết tương đối. Chỉ đọc String.

**Giá trị trả về:**
java.lang.String

### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

Trả về nội dung SVG. Chỉ đọc String.

**Giá trị trả về:**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Lưu hình ảnh SVG dưới dạng tệp EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Tạo hình ảnh SVG mới
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Lưu hình ảnh SVG dưới dạng metafile
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Tạo hình ảnh SVG mới
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Lưu hình ảnh SVG dưới dạng metafile
>      svgImage.writeAsEmf(byteStream);
>      // Thêm metafile vào bộ sưu tập hình ảnh
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |