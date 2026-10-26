---
title: IPdfOptions
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới dạng PDF.
type: docs
url: /vi/com.aspose.slides/ipdfoptions/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới dạng PDF.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. |
| [setTextCompression(int value)](#setTextCompression-int-) | Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Chỉ ra liệu nén hiệu quả nhất (thay vì mặc định) cho mỗi hình ảnh có phải được tự động chọn hay không. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Chỉ ra liệu nén hiệu quả nhất (thay vì mặc định) cho mỗi hình ảnh có phải được tự động chọn hay không. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True để nhúng phông chữ TrueType cho các ký tự ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True để nhúng phông chữ TrueType cho các ký tự ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Xác định liệu tài liệu tạo ra có nên bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Xác định liệu tài liệu tạo ra có nên bao gồm các slide ẩn hay không. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Trả về hoặc đặt một mảng các tên do người dùng xác định của các họ phông chữ mà Aspose.Slides nên coi là chung. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Trả về hoặc đặt một mảng các tên do người dùng xác định của các họ phông chữ mà Aspose.Slides nên coi là chung. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Xác định liệu tất cả ký tự của phông chữ có nên được nhúng hay chỉ một tập con được sử dụng. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Xác định liệu tất cả ký tự của phông chữ có nên được nhúng hay chỉ một tập con được sử dụng. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Chỉ ra liệu văn bản có nên được raster hoá thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Chỉ ra liệu văn bản có nên được raster hoá thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. |
| [getJpegQuality()](#getJpegQuality--) | Trả về hoặc đặt một giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Trả về hoặc đặt một giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. |
| [getCompliance()](#getCompliance--) | Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. |
| [setCompliance(int value)](#setCompliance-int-) | Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. |
| [getPassword()](#getPassword--) | Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Chứa một tập hợp các cờ chỉ định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Chứa một tập hợp các cờ chỉ định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu sang hình ảnh PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu sang hình ảnh PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Trả về hoặc đặt một giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Trả về hoặc đặt một giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True để vẽ khung màu đen quanh mỗi slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True để vẽ khung màu đen quanh mỗi slide. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Lấy hoặc đặt màu trong suốt cho hình ảnh. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Lấy hoặc đặt màu trong suốt cho hình ảnh. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Áp dụng màu trong suốt được chỉ định cho một hình ảnh nếu true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Áp dụng màu trong suốt được chỉ định cho một hình ảnh nếu true. |
| [getInkOptions()](#getInkOptions--) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu được xuất. |
| [getIncludeOleData()](#getIncludeOleData--) | True để chuyển đổi tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True để chuyển đổi tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. Đọc/viết [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Mặc định là [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Trả về:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. Đọc/viết [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Mặc định là [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Chỉ ra liệu nén hiệu quả nhất (thay vì mặc định) cho mỗi hình ảnh có phải được tự động chọn hay không. Nếu đặt thành true, đối với mỗi hình ảnh trong bản trình chiếu, thuật toán nén phù hợp nhất sẽ được chọn, dẫn đến kích thước nhỏ hơn của tài liệu PDF kết quả.

--------------------

Việc chọn tỷ lệ nén hình ảnh tốt nhất tiêu tốn nhiều tài nguyên tính toán và cần thêm RAM, và tùy chọn này mặc định là false.

--------------------

Mặc định là false.

**Trả về:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Chỉ ra liệu nén hiệu quả nhất (thay vì mặc định) cho mỗi hình ảnh có phải được tự động chọn hay không. Nếu đặt thành true, đối với mỗi hình ảnh trong bản trình chiếu, thuật toán nén phù hợp nhất sẽ được chọn, dẫn đến kích thước nhỏ hơn của tài liệu PDF kết quả.

--------------------

Việc chọn tỷ lệ nén hình ảnh tốt nhất tiêu tốn nhiều tài nguyên tính toán và cần thêm RAM, và tùy chọn này mặc định là false.

--------------------

Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True để nhúng phông chữ TrueType cho các ký tự ASCII 32-127. Các phông chữ cho mã ký tự lớn hơn 127 luôn được nhúng. Đọc/viết boolean.

--------------------

Mặc định là **true**.

**Trả về:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True để nhúng phông chữ TrueType cho các ký tự ASCII 32-127. Các phông chữ cho mã ký tự lớn hơn 127 luôn được nhúng. Đọc/viết boolean.

--------------------

Mặc định là **true**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Xác định liệu tài liệu tạo ra có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Xác định liệu tài liệu tạo ra có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Trả về hoặc đặt một mảng các tên do người dùng xác định của các họ phông chữ mà Aspose.Slides nên coi là chung. Đọc/viết String[].

**Trả về:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Trả về hoặc đặt một mảng các tên do người dùng xác định của các họ phông chữ mà Aspose.Slides nên coi là chung. Đọc/viết String[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Xác định liệu tất cả ký tự của phông chữ có nên được nhúng hay chỉ một tập con được sử dụng. Đọc/viết boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Xác định liệu tất cả ký tự của phông chữ có nên được nhúng hay chỉ một tập con được sử dụng. Đọc/viết boolean.

--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Chỉ ra liệu văn bản có nên được raster hoá thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. Cách tiếp cận này có thể nâng cao chất lượng văn bản trong PDF kết quả cho một số phông chữ. Đọc/viết boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Chỉ ra liệu văn bản có nên được raster hoá thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. Cách tiếp cận này có thể nâng cao chất lượng văn bản trong PDF kết quả cho một số phông chữ. Đọc/viết boolean.

--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Trả về hoặc đặt một giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. Đọc/viết byte.

--------------------

Chỉ có hiệu lực khi tài liệu chứa hình ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các hình ảnh trong tài liệu khi lưu ở định dạng PDF. Giá trị có thể dao động từ 0 đến 100, trong đó 0 nghĩa là chất lượng kém nhất nhưng nén tối đa và 100 nghĩa là chất lượng tốt nhất nhưng nén tối thiểu.

Giá trị mặc định là **100**.

**Trả về:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Trả về hoặc đặt một giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. Đọc/viết byte.

--------------------

Chỉ có hiệu lực khi tài liệu chứa hình ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các hình ảnh trong tài liệu khi lưu ở định dạng PDF. Giá trị có thể dao động từ 0 đến 100, trong đó 0 nghĩa là chất lượng kém nhất nhưng nén tối đa và 100 nghĩa là chất lượng tốt nhất nhưng nén tối thiểu.

Giá trị mặc định là **100**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. Đọc/viết [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Mặc định là [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Trả về:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. Đọc/viết [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Mặc định là [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. Đọc/viết String.

**Trả về:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. Đọc/viết String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Chứa một tập hợp các cờ chỉ định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. Xem [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Trả về:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

Chứa một tập hợp các cờ chỉ định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. Xem [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu sang hình ảnh PNG. Đọc/viết boolean.

--------------------

Mặc định là **true**. Tài liệu PDF có thể chứa đồ họa vector và hình ảnh raster. Nếu SaveMetafilesAsPng được đặt thành true thì hình ảnh Metafile nguồn sẽ được chuyển đổi sang định dạng PNG và lưu vào PDF dưới dạng raster. Nếu SaveMetafilesAsPng được đặt thành false thì Metafile nguồn sẽ được chuyển đổi sang đồ họa vector của PDF. Mỗi cách tiếp cận có ưu và nhược điểm. Ví dụ, nếu Metafile được chuyển sang PNG, có thể xảy ra mất một phần chất lượng khi tài liệu được phóng to. Nếu Metafile được chuyển sang đồ họa vector của PDF, có thể xảy ra vấn đề hiệu năng khi xem PDF.

**Trả về:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu sang hình ảnh PNG. Đọc/viết boolean.

--------------------

Mặc định là **true**. Tài liệu PDF có thể chứa đồ họa vector và hình ảnh raster. Nếu SaveMetafilesAsPng được đặt thành true thì hình ảnh Metafile nguồn sẽ được chuyển đổi sang định dạng PNG và lưu vào PDF dưới dạng raster. Nếu SaveMetafilesAsPng được đặt thành false thì Metafile nguồn sẽ được chuyển đổi sang đồ họa vector của PDF. Mỗi cách tiếp cận có ưu và nhược điểm. Ví dụ, nếu Metafile được chuyển sang PNG, có thể xảy ra mất một phần chất lượng khi tài liệu được phóng to. Nếu Metafile được chuyển sang đồ họa vector của PDF, có thể xảy ra vấn đề hiệu năng khi xem PDF.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Trả về hoặc đặt một giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. Đọc/viết float.

Giá trị: Ảnh hưởng của tham số này phụ thuộc vào một số yếu tố. Thuật toán cố gắng đạt kích thước ảnh đầu ra tốt nhất dựa trên giá trị thuộc tính, kích thước ảnh nguồn và kích thước khung ảnh. Sử dụng các giá trị thuộc tính tương tự có thể cho cùng một kết quả. Khuyến cáo sử dụng bước 16 hoặc 32 để thấy hiệu quả.

--------------------

Thuộc tính ảnh hưởng tới kích thước tệp, thời gian xuất và chất lượng ảnh.

Giá trị mặc định là **96**.

**Trả về:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Trả về hoặc đặt một giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. Đọc/viết float.

Giá trị: Ảnh hưởng của tham số này phụ thuộc vào một số yếu tố. Thuật toán cố gắng đạt kích thước ảnh đầu ra tốt nhất dựa trên giá trị thuộc tính, kích thước ảnh nguồn và kích thước khung ảnh. Sử dụng các giá trị thuộc tính tương tự có thể cho cùng một kết quả. Khuyến cáo sử dụng bước 16 hoặc 32 để thấy hiệu quả.

--------------------

Thuộc tính ảnh hưởng tới kích thước tệp, thời gian xuất và chất lượng ảnh.

Giá trị mặc định là **96**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True để vẽ khung màu đen quanh mỗi slide. Đọc/viết boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True để vẽ khung màu đen quanh mỗi slide. Đọc/viết boolean.

--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Lấy hoặc đặt màu trong suốt cho hình ảnh.

Giá trị: Màu trong suốt của hình ảnh.

**Trả về:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Lấy hoặc đặt màu trong suốt cho hình ảnh.

Giá trị: Màu trong suốt của hình ảnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Áp dụng màu trong suốt được chỉ định cho một hình ảnh nếu true.

**Trả về:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Áp dụng màu trong suốt được chỉ định cho một hình ảnh nếu true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu được xuất. Chỉ-đọc [IInkOptions](../../com.aspose.slides/iinkoptions)

**Trả về:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True để chuyển đổi tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. Đọc/viết boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Mặc định là **false**.

**Trả về:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True để chuyển đổi tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. Đọc/viết boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |