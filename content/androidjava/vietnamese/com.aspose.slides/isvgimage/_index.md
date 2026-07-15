---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho một hình ảnh SVG.
type: docs
url: /vi/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Đại diện cho một hình ảnh SVG.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Trả về nội dung SVG. |
| [getSvgData()](#getSvgData--) | Trả về dữ liệu SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Trả về giao diện callback được sử dụng để giải quyết tài nguyên bên ngoài trong quá trình nhập tài liệu SVG. |
| [getBaseUri()](#getBaseUri--) | Trả về URI cơ sở của SVG được chỉ định. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Lưu hình ảnh SVG dưới dạng tệp EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Trả về nội dung SVG. Chỉ đọc String.

**Trả về:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Trả về dữ liệu SVG. Chỉ đọc byte[].

**Trả về:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Trả về giao diện callback được sử dụng để giải quyết tài nguyên bên ngoài trong quá trình nhập tài liệu SVG. Chỉ đọc [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Trả về:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Trả về URI cơ sở của SVG được chỉ định. Được sử dụng để giải quyết các liên kết tương đối. Chỉ đọc String.

**Trả về:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Lưu hình ảnh SVG dưới dạng tệp EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
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