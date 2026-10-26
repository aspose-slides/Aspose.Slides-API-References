---
title: IPptxOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho các tùy chọn khi lưu bản trình bày OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /vi/com.aspose.slides/ipptxoptions/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Đại diện cho các tùy chọn khi lưu bản trình bày OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getConformance()](#getConformance--) | Xác định lớp tuân thủ mà tài liệu Presentation tuân theo. |
| [setConformance(int value)](#setConformance-int-) | Xác định lớp tuân thủ mà tài liệu Presentation tuân theo. |
| [getZip64Mode()](#getZip64Mode--) | Xác định xem định dạng ZIP64 có được sử dụng cho tài liệu Presentation hay không. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Xác định xem định dạng ZIP64 có được sử dụng cho tài liệu Presentation hay không. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Xác định xem hình thu nhỏ của bản trình bày có được làm mới hay không. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Xác định xem hình thu nhỏ của bản trình bày có được làm mới hay không. |
| [getCompressionLevel()](#getCompressionLevel--) | Xác định mức nén được sử dụng khi lưu tài liệu bản trình bày. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Xác định mức nén được sử dụng khi lưu tài liệu bản trình bày. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Xác định lớp tuân thủ mà tài liệu Presentation tuân theo. Giá trị mặc định là [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Trả về:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Xác định lớp tuân thủ mà tài liệu Presentation tuân theo. Giá trị mặc định là [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

Xác định xem định dạng ZIP64 có được sử dụng cho tài liệu Presentation hay không. Giá trị mặc định là [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
```

Xác định xem định dạng ZIP64 có được sử dụng cho tài liệu Presentation hay không. Giá trị mặc định là [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```

Xác định xem hình thu nhỏ của bản trình bày có được làm mới hay không. Đọc/ghi boolean. Giá trị mặc định là **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Khi giá trị tùy chọn là **true**, hình thu nhỏ mới sẽ được tạo.

Khi giá trị tùy chọn là **false**, hình thu nhỏ hiện tại sẽ được lưu nguyên trạng.

**Trả về:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Xác định xem hình thu nhỏ của bản trình bày có được làm mới hay không. Đọc/ghi boolean. Giá trị mặc định là **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Khi giá trị tùy chọn là **true**, hình thu nhỏ mới sẽ được tạo.

Khi giá trị tùy chọn là **false**, hình thu nhỏ hiện tại sẽ được lưu nguyên trạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

Xác định mức nén được sử dụng khi lưu tài liệu bản trình bày. Giá trị mặc định là [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Mức nén cao hơn tạo ra các tệp nhỏ hơn nhưng yêu cầu thời gian xử lý lâu hơn. Tỷ lệ nén thực tế phụ thuộc vào nội dung của bản trình bày.

**Trả về:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

Xác định mức nén được sử dụng khi lưu tài liệu bản trình bày. Giá trị mặc định là [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Mức nén cao hơn tạo ra các tệp nhỏ hơn nhưng yêu cầu thời gian xử lý lâu hơn. Tỷ lệ nén thực tế phụ thuộc vào nội dung của bản trình bày.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |