---
title: IPdfOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu ở định dạng Pdf.
type: docs
url: /vi/com.aspose.slides/ipdfoptions/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu ở định dạng Pdf.

## Phương thức

| Method | Description |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. |
| [setTextCompression(int value)](#setTextCompression-int-) | Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Cho biết có nên tự động chọn nén hiệu quả nhất (thay vì mặc định) cho mỗi hình ảnh hay không. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Cho biết có nên tự động chọn nén hiệu quả nhất (thay vì mặc định) cho mỗi hình ảnh hay không. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Đúng để nhúng phông chữ TrueType cho các ký tự ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Đúng để nhúng phông chữ TrueType cho các ký tự ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Xác định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Xác định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Trả về hoặc đặt một mảng các tên phông chữ do người dùng xác định mà Aspose.Slides nên coi là chung. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Trả về hoặc đặt một mảng các tên phông chữ do người dùng xác định mà Aspose.Slides nên coi là chung. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Xác định xem có nên nhúng tất cả ký tự của phông chữ hay chỉ một phần được sử dụng. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Xác định xem có nên nhúng tất cả ký tự của phông chữ hay chỉ một phần được sử dụng. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Cho biết liệu văn bản có nên raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Cho biết liệu văn bản có nên raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. |
| [getJpegQuality()](#getJpegQuality--) | Trả về hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Trả về hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. |
| [getCompliance()](#getCompliance--) | Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. |
| [setCompliance(int value)](#setCompliance-int-) | Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. |
| [getPassword()](#getPassword--) | Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Chứa một tập hợp các cờ chỉ định các quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Chứa một tập hợp các cờ chỉ định các quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Đúng để chuyển tất cả các metafile được sử dụng trong bản thuyết trình sang hình ảnh PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Đúng để chuyển tất cả các metafile được sử dụng trong bản thuyết trình sang hình ảnh PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Trả về hoặc đặt giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Trả về hoặc đặt giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Đúng để vẽ khung đen quanh mỗi slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Đúng để vẽ khung đen quanh mỗi slide. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản thuyết trình [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản thuyết trình [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Lấy hoặc đặt màu trong suốt cho hình ảnh. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Lấy hoặc đặt màu trong suốt cho hình ảnh. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Áp dụng màu trong suốt đã chỉ định cho hình ảnh nếu đúng. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Áp dụng màu trong suốt đã chỉ định cho hình ảnh nếu đúng. |
| [getInkOptions()](#getInkOptions--) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu xuất. |
| [getIncludeOleData()](#getIncludeOleData--) | Đúng để chuyển tất cả dữ liệu OLE từ bản thuyết trình sang các tệp nhúng trong PDF kết quả. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Đúng để chuyển tất cả dữ liệu OLE từ bản thuyết trình sang các tệp nhúng trong PDF kết quả. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. Đọc/ghi [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Mặc định là [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Trả về:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. Đọc/ghi [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

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

Cho biết có nên tự động chọn nén hiệu quả nhất (thay vì mặc định) cho mỗi hình ảnh hay không. Nếu đặt thành true, đối với mỗi hình ảnh trong bản thuyết trình thuật toán nén phù hợp nhất sẽ được chọn, giúp giảm kích thước tài liệu PDF cuối cùng.

--------------------

Việc chọn tỷ lệ nén hình ảnh tốt nhất tốn nhiều tính toán và bộ nhớ RAM, và tùy chọn này mặc định là false.

--------------------

Mặc định là false.

**Trả về:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Cho biết có nên tự động chọn nén hiệu quả nhất (thay vì mặc định) cho mỗi hình ảnh hay không. Nếu đặt thành true, đối với mỗi hình ảnh trong bản thuyết trình thuật toán nén phù hợp nhất sẽ được chọn, giúp giảm kích thước tài liệu PDF cuối cùng.

--------------------

Việc chọn tỷ lệ nén hình ảnh tốt nhất tốn nhiều tính toán và bộ nhớ RAM, và tùy chọn này mặc định là false.

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

Đúng để nhúng phông chữ TrueType cho các ký tự ASCII 32-127. Phông chữ cho các mã ký tự lớn hơn 127 luôn được nhúng. Đọc/ghi boolean.

--------------------

Mặc định là **true**.

**Trả về:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

Đúng để nhúng phông chữ TrueType cho các ký tự ASCII 32-127. Phông chữ cho các mã ký tự lớn hơn 127 luôn được nhúng. Đọc/ghi boolean.

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

Xác định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Xác định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Trả về hoặc đặt một mảng các tên phông chữ do người dùng xác định mà Aspose.Slides nên coi là chung. Đọc/ghi String[].

**Trả về:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Trả về hoặc đặt một mảng các tên phông chữ do người dùng xác định mà Aspose.Slides nên coi là chung. Đọc/ghi String[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Xác định xem có nên nhúng tất cả ký tự của phông chữ hay chỉ một phần được sử dụng. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Xác định xem có nên nhúng tất cả ký tự của phông chữ hay chỉ một phần được sử dụng. Đọc/ghi boolean.

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

Cho biết liệu văn bản có nên raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. Cách tiếp cận này có thể cải thiện chất lượng văn bản trong PDF kết quả cho một số phông chữ. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Cho biết liệu văn bản có nên raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. Cách tiếp cận này có thể cải thiện chất lượng văn bản trong PDF kết quả cho một số phông chữ. Đọc/ghi boolean.

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

Trả về hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. Đọc/ghi byte.

--------------------

Chỉ có hiệu lực khi tài liệu chứa các hình ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các hình ảnh trong tài liệu khi lưu dưới định dạng PDF. Giá trị có thể từ 0 đến 100, trong đó 0 là chất lượng kém nhất nhưng nén tối đa và 100 là chất lượng tốt nhất nhưng nén tối thiểu.

Giá trị mặc định là **100**.

**Trả về:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Trả về hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. Đọc/ghi byte.

--------------------

Chỉ có hiệu lực khi tài liệu chứa các hình ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các hình ảnh trong tài liệu khi lưu dưới định dạng PDF. Giá trị có thể từ 0 đến 100, trong đó 0 là chất lượng kém nhất nhưng nén tối đa và 100 là chất lượng tốt nhất nhưng nén tối thiểu.

Giá trị mặc định là **100**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. Đọc/ghi [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Mặc định là [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Trả về:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. Đọc/ghi [PdfCompliance](../../com.aspose.slides/pdfcompliance).

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

Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. Đọc/ghi String.

**Trả về:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Chứa một tập hợp các cờ chỉ định các quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. Xem [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Chứa một tập hợp các cờ chỉ định các quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. Xem [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Đúng để chuyển tất cả các metafile được sử dụng trong bản thuyết trình sang hình ảnh PNG. Đọc/ghi boolean.

--------------------

Mặc định là **true**. Tài liệu PDF có thể chứa đồ họa vector và hình ảnh raster. Nếu SaveMetafilesAsPng được đặt là true, hình ảnh Metafile nguồn sẽ được chuyển sang định dạng PNG và lưu vào PDF dưới dạng raster. Nếu SaveMetafilesAsPng được đặt là false, Metafile nguồn sẽ được chuyển sang đồ họa vector PDF. Mỗi cách đều có ưu và nhược điểm. Ví dụ, nếu Metafile được chuyển sang PNG, một số mất chất lượng có thể xảy ra khi thu phóng tài liệu kết quả. Nếu Metafile được chuyển sang đồ họa vector PDF, có thể xảy ra vấn đề hiệu năng trong công cụ xem PDF.

**Trả về:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Đúng để chuyển tất cả các metafile được sử dụng trong bản thuyết trình sang hình ảnh PNG. Đọc/ghi boolean.

--------------------

Mặc định là **true**. Tài liệu PDF có thể chứa đồ họa vector và hình ảnh raster. Nếu SaveMetafilesAsPng được đặt là true, hình ảnh Metafile nguồn sẽ được chuyển sang định dạng PNG và lưu vào PDF dưới dạng raster. Nếu SaveMetafilesAsPng được đặt là false, Metafile nguồn sẽ được chuyển sang đồ họa vector PDF. Mỗi cách đều có ưu và nhược điểm. Ví dụ, nếu Metafile được chuyển sang PNG, một số mất chất lượng có thể xảy ra khi thu phóng tài liệu kết quả. Nếu Metafile được chuyển sang đồ họa vector PDF, có thể xảy ra vấn đề hiệu năng trong công cụ xem PDF.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Trả về hoặc đặt giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. Đọc/ghi float.

Giá trị: Ảnh hưởng của tham số này phụ thuộc vào một số yếu tố. Thuật toán cố gắng đưa ra kích thước hình ảnh đầu ra tốt nhất dựa trên giá trị thuộc tính, kích thước ảnh nguồn và kích thước khung ảnh. Sử dụng các giá trị thuộc tính tương tự có thể cho ra kết quả giống nhau. Đề nghị dùng bước 16 hoặc 32 để thấy hiệu ứng rõ rệt.

--------------------

Thuộc tính ảnh hưởng đến kích thước tệp, thời gian xuất và chất lượng hình ảnh.

Giá trị mặc định là **96**.

**Trả về:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Trả về hoặc đặt giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. Đọc/ghi float.

Giá trị: Ảnh hưởng của tham số này phụ thuộc vào một số yếu tố. Thuật toán cố gắng đưa ra kích thước hình ảnh đầu ra tốt nhất dựa trên giá trị thuộc tính, kích thước ảnh nguồn và kích thước khung ảnh. Sử dụng các giá trị thuộc tính tương tự có thể cho ra kết quả giống nhau. Đề nghị dùng bước 16 hoặc 32 để thấy hiệu ứng rõ rệt.

--------------------

Thuộc tính ảnh hưởng đến kích thước tệp, thời gian xuất và chất lượng hình ảnh.

Giá trị mặc định là **96**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Đúng để vẽ khung đen quanh mỗi slide. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Đúng để vẽ khung đen quanh mỗi slide. Đọc/ghi boolean.

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

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản thuyết trình [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản thuyết trình [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract Color getImageTransparentColor()
```

Lấy hoặc đặt màu trong suốt cho hình ảnh.

Giá trị: Màu trong suốt của hình ảnh.

**Trả về:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

Lấy hoặc đặt màu trong suốt cho hình ảnh.

Giá trị: Màu trong suốt của hình ảnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Áp dụng màu trong suốt đã chỉ định cho hình ảnh nếu đúng.

**Trả về:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Áp dụng màu trong suốt đã chỉ định cho hình ảnh nếu đúng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu xuất. Chỉ đọc [IInkOptions](../../com.aspose.slides/iinkoptions)

**Trả về:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

Đúng để chuyển tất cả dữ liệu OLE từ bản thuyết trình sang các tệp nhúng trong PDF kết quả. Đọc/ghi boolean.

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

Đúng để chuyển tất cả dữ liệu OLE từ bản thuyết trình sang các tệp nhúng trong PDF kết quả. Đọc/ghi boolean.

--------------------

> ```
public abstract void setIncludeOleData(boolean value)
```

--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |