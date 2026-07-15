---
title: PptxOptions
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Đại diện cho các tùy chọn khi lưu bản trình chiếu OpenXml PPTX, PPSX, POTX, PPTM, PPSM, POTM.
type: docs
url: /vi/com.aspose.slides/pptxoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Đại diện cho các tùy chọn khi lưu bản trình chiếu OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Hàm tạo

| Constructor | Description |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Tạo một thể hiện mới của PptxOptions |
## Phương thức

| Method | Description |
| --- | --- |
| [getConformance()](#getConformance--) | Xác định lớp tương thích mà tài liệu Presentation tuân theo. |
| [setConformance(int value)](#setConformance-int-) | Xác định lớp tương thích mà tài liệu Presentation tuân theo. |
| [getZip64Mode()](#getZip64Mode--) | Xác định xem định dạng ZIP64 có được sử dụng cho tài liệu Presentation hay không. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Xác định xem định dạng ZIP64 có được sử dụng cho tài liệu Presentation hay không. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Xác định xem hình thu nhỏ của bản trình chiếu có được làm mới hay không. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Xác định xem hình thu nhỏ của bản trình chiếu có được làm mới hay không. |
| [getCompressionLevel()](#getCompressionLevel--) | Xác định mức nén được sử dụng khi lưu tài liệu bản trình chiếu. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Xác định mức nén được sử dụng khi lưu tài liệu bản trình chiếu. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

Tạo một thể hiện mới của PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Xác định lớp tương thích mà tài liệu Presentation tuân theo. Giá trị mặc định là [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Trả về:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Xác định lớp tương thích mà tài liệu Presentation tuân theo. Giá trị mặc định là [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
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
public final void setZip64Mode(int value)
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```

Xác định xem hình thu nhỏ của bản trình chiếu có được làm mới hay không. Đọc/ghi boolean. Giá trị mặc định là **true**.

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

Khi giá trị tùy chọn là **false**, hình thu nhỏ hiện tại sẽ được lưu nguyên như vậy.

**Trả về:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

Xác định xem hình thu nhỏ của bản trình chiếu có được làm mới hay không. Đọc/ghi boolean. Giá trị mặc định là **true**.

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

Khi giá trị tùy chọn là **false**, hình thu nhỏ hiện tại sẽ được lưu nguyên như vậy.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

Xác định mức nén được sử dụng khi lưu tài liệu bản trình chiếu. Giá trị mặc định là [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Mức nén cao hơn tạo ra các tệp tin nhỏ hơn nhưng đòi hỏi thời gian xử lý nhiều hơn. Tỷ lệ nén thực tế phụ thuộc vào nội dung của bản trình chiếu.

**Trả về:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

Xác định mức nén được sử dụng khi lưu tài liệu bản trình chiếu. Giá trị mặc định là [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Mức nén cao hơn tạo ra các tệp tin nhỏ hơn nhưng đòi hỏi thời gian xử lý nhiều hơn. Tỷ lệ nén thực tế phụ thuộc vào nội dung của bản trình chiếu.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |