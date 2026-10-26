---
title: PdfOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới định dạng PDF.
type: docs
url: /vi/com.aspose.slides/pdfoptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới định dạng Pdf.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Khởi tạo lớp PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Đặt chất lượng Jpeg
>      pdfOptions.setJpegQuality((byte)90);
>      // Đặt hành vi cho metafiles
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Đặt mức nén văn bản
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Xác định tiêu chuẩn PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Lưu bản trình chiếu dưới dạng PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Khởi tạo một lớp Presentation đại diện cho tệp PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Khởi tạo lớp PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Thêm các slide ẩn
>      pdfOptions.setShowHiddenSlides(true);
>      // Lưu bản trình chiếu dưới dạng PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Khởi tạo một đối tượng Presentation đại diện cho tệp PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Khởi tạo lớp PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Đặt mật khẩu PDF và các quyền truy cập
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Lưu bản trình chiếu dưới dạng PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Khởi tạo một đối tượng Presentation đại diện cho tệp trình chiếu
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Đặt loại và kích thước slide
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Hàm khởi tạo mặc định. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Xác định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Xác định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. |
| [getTextCompression()](#getTextCompression--) | Xác định loại nén sẽ được sử dụng cho toàn bộ nội dung văn bản trong tài liệu. |
| [setTextCompression(int value)](#setTextCompression-int-) | Xác định loại nén sẽ được sử dụng cho toàn bộ nội dung văn bản trong tài liệu. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Chỉ ra liệu nén hiệu quả nhất (thay vì nén mặc định) cho mỗi hình ảnh có phải được chọn tự động hay Không. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Chỉ ra liệu nén hiệu quả nhất (thay vì nén mặc định) cho mỗi hình ảnh có phải được chọn tự động hay Không. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Xác định xem Aspose.Slides có nhúng các phông chữ chung cho văn bản ASCII (phạm vi mã 33..127) hay không. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Xác định xem Aspose.Slides có nhúng các phông chữ chung cho văn bản ASCII (phạm vi mã 33..127) hay không. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Lấy hoặc đặt một mảng các tên phông chữ do người dùng định nghĩa mà Aspose.Slides nên xem là chung. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Lấy hoặc đặt một mảng các tên phông chữ do người dùng định nghĩa mà Aspose.Slides nên xem là chung. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Xác định xem tất cả các ký tự của phông chữ có nên được nhúng hay chỉ một tập con được sử dụng. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Xác định xem tất cả các ký tự của phông chữ có nên được nhúng hay chỉ một tập con được sử dụng. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Chỉ ra liệu văn bản có nên được raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu chữ đậm hay không. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Chỉ ra liệu văn bản có nên được raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu chữ đậm hay không. |
| [getJpegQuality()](#getJpegQuality--) | Lấy hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Lấy hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. |
| [getCompliance()](#getCompliance--) | Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. |
| [setCompliance(int value)](#setCompliance-int-) | Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. |
| [getPassword()](#getPassword--) | Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Chứa một tập hợp các cờ xác định các quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Chứa một tập hợp các cờ xác định các quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Đặt thành true để chuyển đổi tất cả các metafile sử dụng trong bản trình chiếu sang hình ảnh PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Đặt thành true để chuyển đổi tất cả các metafile sử dụng trong bản trình chiếu sang hình ảnh PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Lấy hoặc đặt giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Lấy hoặc đặt giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Đặt thành true để vẽ khung màu đen quanh mỗi slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Đặt thành true để vẽ khung màu đen quanh mỗi slide. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Lấy hoặc đặt màu trong suốt của hình ảnh. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Lấy hoặc đặt màu trong suốt của hình ảnh. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Áp dụng màu trong suốt đã chỉ định cho hình ảnh nếu true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Áp dụng màu trong suốt đã chỉ định cho hình ảnh nếu true. |
| [getIncludeOleData()](#getIncludeOleData--) | Đặt thành true để chuyển đổi tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Đặt thành true để chuyển đổi tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Hàm khởi tạo mặc định.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất. Chỉ đọc [IInkOptions](../../com.aspose.slides/iinkoptions)

**Trả về:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Xác định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Xác định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Xác định loại nén sẽ được sử dụng cho toàn bộ nội dung văn bản trong tài liệu. Đọc/ghi [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Mặc định là [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Trả về:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Xác định loại nén sẽ được sử dụng cho toàn bộ nội dung văn bản trong tài liệu. Đọc/ghi [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Mặc định là [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Chỉ ra liệu nén hiệu quả nhất (thay vì nén mặc định) cho mỗi hình ảnh có phải được chọn tự động hay không. Nếu đặt thành true, đối với mỗi hình ảnh trong bản trình chiếu thuật toán nén phù hợp nhất sẽ được chọn, giúp giảm kích thước tài liệu PDF kết quả.

Việc lựa chọn tỉ lệ nén hình ảnh tốt nhất tốn tính toán cao và tiêu tốn thêm bộ nhớ RAM, và tùy chọn này mặc định là false.

--------------------

Mặc định là false.

**Trả về:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Chỉ ra liệu nén hiệu quả nhất (thay vì nén mặc định) cho mỗi hình ảnh có phải được chọn tự động hay không. Nếu đặt thành true, đối với mỗi hình ảnh trong bản trình chiếu thuật toán nén phù hợp nhất sẽ được chọn, giúp giảm kích thước tài liệu PDF kết quả.

Việc lựa chọn tỉ lệ nén hình ảnh tốt nhất tốn tính toán cao và tiêu tốn thêm bộ nhớ RAM, và tùy chọn này mặc định là false.

--------------------

Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Xác định xem Aspose.Slides có nhúng các phông chữ chung cho văn bản ASCII (phạm vi mã 33..127) hay không. Các phông chữ cho mã ký tự lớn hơn 127 luôn được nhúng. Danh sách phông chữ chung bao gồm 14 phông chữ cơ bản của PDF và các phông chữ do người dùng chỉ định thêm. Đọc/ghi boolean.

--------------------

Mặc định là **true**.

**Trả về:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Xác định xem Aspose.Slides có nhúng các phông chữ chung cho văn bản ASCII (phạm vi mã 33..127) hay không. Các phông chữ cho mã ký tự lớn hơn 127 luôn được nhúng. Danh sách phông chữ chung bao gồm 14 phông chữ cơ bản của PDF và các phông chữ do người dùng chỉ định thêm. Đọc/ghi boolean.

--------------------

Mặc định là **true**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Lấy hoặc đặt một mảng các tên phông chữ do người dùng định nghĩa mà Aspose.Slides nên xem là chung. Read/write String[].

**Trả về:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Lấy hoặc đặt một mảng các tên phông chữ do người dùng định nghĩa mà Aspose.Slides nên xem là chung. Read/write String[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Xác định xem tất cả các ký tự của phông chữ có nên được nhúng hay chỉ một tập con được sử dụng. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Xác định xem tất cả các ký tự của phông chữ có nên được nhúng hay chỉ một tập con được sử dụng. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Chỉ ra liệu văn bản có nên được raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu chữ đậm hay không. Cách này có thể nâng cao chất lượng văn bản trong PDF kết quả đối với một số phông chữ. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Chỉ ra liệu văn bản có nên được raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu chữ đậm hay không. Cách này có thể nâng cao chất lượng văn bản trong PDF kết quả đối với một số phông chữ. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Lấy hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. Đọc/ghi byte.

--------------------

Chỉ có hiệu lực khi tài liệu chứa hình ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các hình ảnh trong tài liệu khi lưu ở định dạng PDF. Giá trị có thể thay đổi từ 0 đến 100, trong đó 0 nghĩa là chất lượng thấp nhất nhưng nén tối đa và 100 nghĩa là chất lượng tốt nhất nhưng nén tối thiểu.

Giá trị mặc định là **100**.

**Trả về:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Lấy hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. Đọc/ghi byte.

--------------------

Chỉ có hiệu lực khi tài liệu chứa hình ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các hình ảnh trong tài liệu khi lưu ở định dạng PDF. Giá trị có thể thay đổi từ 0 đến 100, trong đó 0 nghĩa là chất lượng thấp nhất nhưng nén tối đa và 100 nghĩa là chất lượng tốt nhất nhưng nén tối thiểu.

Giá trị mặc định là **100**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. Đọc/ghi [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Mặc định là [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Trả về:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
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
public final String getPassword()
```

Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. Đọc/ghi String.

**Trả về:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Chứa một tập hợp các cờ xác định các quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. Xem [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final void setAccessPermissions(int value)
```

Chứa một tập hợp các cờ xác định các quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. Xem [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final boolean getSaveMetafilesAsPng()
```

Đặt thành true để chuyển đổi tất cả các metafile sử dụng trong bản trình chiếu sang hình ảnh PNG. Đọc/ghi boolean.

--------------------

Mặc định là **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

**Trả về:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Đặt thành true để chuyển đổi tất cả các metafile sử dụng trong bản trình chiếu sang hình ảnh PNG. Đọc/ghi boolean.

--------------------

Mặc định là **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Lấy hoặc đặt giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. Đọc/ghi float.

Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

--------------------

Property affects on file size, time of export and image quality.

Giá trị mặc định là **96**.

**Trả về:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Lấy hoặc đặt giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. Đọc/ghi float.

Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

--------------------

Property affects on file size, time of export and image quality.

Giá trị mặc định là **96**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Đặt thành true để vẽ khung màu đen quanh mỗi slide. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Đặt thành true để vẽ khung màu đen quanh mỗi slide. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Lấy hoặc đặt màu trong suốt của hình ảnh.

Value: The color of the image transparent.

**Trả về:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Lấy hoặc đặt màu trong suốt của hình ảnh.

Value: The color of the image transparent.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Áp dụng màu trong suốt đã chỉ định cho hình ảnh nếu true.

**Trả về:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Áp dụng màu trong suốt đã chỉ định cho hình ảnh nếu true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Đặt thành true để chuyển đổi tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. Đọc/ghi  boolean .

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

Mặc định là  **false** .

**Trả về:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Đặt thành true để chuyển đổi tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. Đọc/ghi  boolean .

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

Mặc định là  **false** .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |