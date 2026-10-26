---
title: PdfOptions
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng Pdf.
type: docs
url: /vi/com.aspose.slides/pdfoptions/
---
**Kế thừa:**
[com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng Pdf.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Tạo một đối tượng PdfOptions class
>      PdfOptions pdfOptions = new PdfOptions();
>      // Đặt chất lượng Jpeg
>      pdfOptions.setJpegQuality((byte)90);
>      // Đặt hành vi cho metafiles
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Đặt mức nén văn bản
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Xác định tiêu chuẩn PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Lưu bản trình chiếu thành PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Tạo một đối tượng Presentation đại diện cho tệp PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Tạo một đối tượng PdfOptions class
>      PdfOptions pdfOptions = new PdfOptions();
>      // Thêm các slide ẩn
>      pdfOptions.setShowHiddenSlides(true);
>      // Lưu bản trình chiếu thành PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Tạo một đối tượng Presentation đại diện cho tệp PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Tạo một đối tượng PdfOptions class
>      PdfOptions pdfOptions = new PdfOptions();
>      // Đặt mật khẩu PDF và quyền truy cập
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Lưu bản trình chiếu thành PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Tạo một đối tượng Presentation đại diện cho tệp trình chiếu
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
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Hàm khởi tạo mặc định. |
## Methods

| Method | Description |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Xác định xem tài liệu tạo ra có bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Xác định xem tài liệu tạo ra có bao gồm các slide ẩn hay không. |
| [getTextCompression()](#getTextCompression--) | Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. |
| [setTextCompression(int value)](#setTextCompression-int-) | Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Cho biết liệu nén hiệu quả nhất (thay vì nén mặc định) cho mỗi ảnh có được tự động chọn hay không. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Cho biết liệu nén hiệu quả nhất (thay vì nén mặc định) cho mỗi ảnh có được tự động chọn hay không. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Xác định liệu Aspose.Slides có nhúng các phông chữ chung cho văn bản ASCII (phạm vi mã 33..127) hay không. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Xác định liệu Aspose.Slides có nhúng các phông chữ chung cho văn bản ASCII (phạm vi mã 33..127) hay không. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Trả về hoặc đặt một mảng các tên phông chữ do người dùng định nghĩa mà Aspose.Slides nên coi là chung. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Trả về hoặc đặt một mảng các tên phông chữ do người dùng định nghĩa mà Aspose.Slides nên coi là chung. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Xác định liệu tất cả ký tự của phông chữ có được nhúng hay chỉ nhúng một tập con được sử dụng. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Xác định liệu tất cả ký tự của phông chữ có được nhúng hay chỉ nhúng một tập con được sử dụng. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Chỉ ra liệu văn bản có nên raster hoá thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Chỉ ra liệu văn bản có nên raster hoá thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. |
| [getJpegQuality()](#getJpegQuality--) | Trả về hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Trả về hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. |
| [getCompliance()](#getCompliance--) | Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo ra. |
| [setCompliance(int value)](#setCompliance-int-) | Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo ra. |
| [getPassword()](#getPassword--) | Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Chứa một tập các cờ xác định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Chứa một tập các cờ xác định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Đặt true để chuyển tất cả các metafile được sử dụng trong bản trình chiếu thành ảnh PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Đặt true để chuyển tất cả các metafile được sử dụng trong bản trình chiếu thành ảnh PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Trả về hoặc đặt giá trị xác định độ phân giải của các ảnh trong tài liệu PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Trả về hoặc đặt giá trị xác định độ phân giải của các ảnh trong tài liệu PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Đặt true để vẽ khung màu đen quanh mỗi slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Đặt true để vẽ khung màu đen quanh mỗi slide. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Lấy hoặc đặt màu trong suốt của ảnh. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Lấy hoặc đặt màu trong suốt của ảnh. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Áp dụng màu trong suốt chỉ định cho ảnh nếu đặt true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Áp dụng màu trong suốt chỉ định cho ảnh nếu đặt true. |
| [getIncludeOleData()](#getIncludeOleData--) | Đặt true để chuyển tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Đặt true để chuyển tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. |
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
| Parameter | Type | Description |
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

Xác định xem tài liệu tạo ra có bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Xác định xem tài liệu tạo ra có bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. Đọc/ghi [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Mặc định là [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Trả về:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Xác định loại nén sẽ được sử dụng cho tất cả nội dung văn bản trong tài liệu. Đọc/ghi [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Mặc định là [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Cho biết liệu nén hiệu quả nhất (thay vì nén mặc định) cho mỗi ảnh có được tự động chọn hay không. Nếu đặt true, mỗi ảnh trong bản trình chiếu sẽ được chọn thuật toán nén phù hợp nhất, giúp giảm kích thước tài liệu PDF kết quả.

--------------------

Việc chọn tỷ lệ nén ảnh tốt nhất tốn nhiều tính toán và tiêu tốn thêm RAM, và tùy chọn này mặc định là false.

--------------------

Mặc định là false.

**Trả về:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Cho biết liệu nén hiệu quả nhất (thay vì nén mặc định) cho mỗi ảnh có được tự động chọn hay không. Nếu đặt true, mỗi ảnh trong bản trình chiếu sẽ được chọn thuật toán nén phù hợp nhất, giúp giảm kích thước tài liệu PDF kết quả.

--------------------

Việc chọn tỷ lệ nén ảnh tốt nhất tốn nhiều tính toán và tiêu tốn thêm RAM, và tùy chọn này mặc định là false.

--------------------

Mặc định là false.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Xác định liệu Aspose.Slides có nhúng các phông chữ chung cho văn bản ASCII (phạm vi mã 33..127) hay không. Các phông chữ cho mã ký tự lớn hơn 127 luôn được nhúng. Danh sách phông chữ chung bao gồm 14 phông chữ cơ bản của PDF và các phông chữ do người dùng chỉ định. Đọc/ghi boolean.

--------------------

Mặc định là **true**.

**Trả về:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Xác định liệu Aspose.Slides có nhúng các phông chữ chung cho văn bản ASCII (phạm vi mã 33..127) hay không. Các phông chữ cho mã ký tự lớn hơn 127 luôn được nhúng. Danh sách phông chữ chung bao gồm 14 phông chữ cơ bản của PDF và các phông chữ do người dùng chỉ định. Đọc/ghi boolean.

--------------------

Mặc định là **true**.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Trả về hoặc đặt một mảng các tên phông chữ do người dùng định nghĩa mà Aspose.Slides nên coi là chung. Đọc/ghi String[].

**Trả về:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Trả về hoặc đặt một mảng các tên phông chữ do người dùng định nghĩa mà Aspose.Slides nên coi là chung. Đọc/ghi String[].

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Xác định liệu tất cả ký tự của phông chữ có được nhúng hay chỉ nhúng một tập con được sử dụng. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Xác định liệu tất cả ký tự của phông chữ có được nhúng hay chỉ nhúng một tập con được sử dụng. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Chỉ ra liệu văn bản có nên raster hoá thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. Cách tiếp cận này có thể cải thiện chất lượng văn bản trong PDF kết quả đối với một số phông chữ. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Chỉ ra liệu văn bản có nên raster hoá thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. Cách tiếp cận này có thể cải thiện chất lượng văn bản trong PDF kết quả đối với một số phông chữ. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Trả về hoặc đặt một giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. Đọc/ghi byte.

--------------------

Chỉ có hiệu lực khi tài liệu chứa ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các ảnh trong tài liệu khi lưu ở định dạng PDF. Giá trị có thể từ 0 tới 100, trong đó 0 là chất lượng thấp nhất nhưng nén tối đa và 100 là chất lượng cao nhất nhưng nén tối thiểu.

Giá trị mặc định là **100**.

**Trả về:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Trả về hoặc đặt một giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. Đọc/ghi byte.

--------------------

Chỉ có hiệu lực khi tài liệu chứa ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các ảnh trong tài liệu khi lưu ở định dạng PDF. Giá trị có thể từ 0 tới 100, trong đó 0 là chất lượng thấp nhất nhưng nén tối đa và 100 là chất lượng cao nhất nhưng nén tối thiểu.

Giá trị mặc định là **100**.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo ra. Đọc/ghi [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Mặc định là [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Trả về:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo ra. Đọc/ghi [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Mặc định là [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Tham số:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Chứa một tập các cờ xác định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. Xem [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Chứa một tập các cờ xác định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. Xem [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
public final void setAccessPermissions(int value)
```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Đặt true để chuyển tất cả các metafile được sử dụng trong bản trình chiếu thành ảnh PNG. Đọc/ghi boolean.

--------------------

Mặc định là **true**. Tài liệu PDF có thể chứa đồ họa vector và ảnh raster. Nếu SaveMetafilesAsPng được đặt true, ảnh Metafile nguồn sẽ được chuyển sang định dạng PNG và lưu vào PDF dưới dạng ảnh raster. Nếu SaveMetafilesAsPng được đặt false, Metafile nguồn sẽ được chuyển sang đồ họa vector PDF. Mỗi cách có ưu và nhược điểm. Ví dụ, nếu Metafile được chuyển sang PNG, có thể xảy ra mất chất lượng khi tài liệu kết quả được phóng to. Nếu Metafile được chuyển sang đồ họa vector PDF, có thể gặp vấn đề hiệu năng khi xem PDF.

**Trả về:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Đặt true để chuyển tất cả các metafile được sử dụng trong bản trình chiếu thành ảnh PNG. Đọc/ghi boolean.

--------------------

Mặc định là **true**. Tài liệu PDF có thể chứa đồ họa vector và ảnh raster. Nếu SaveMetafilesAsPng được đặt true, ảnh Metafile nguồn sẽ được chuyển sang định dạng PNG và lưu vào PDF dưới dạng ảnh raster. Nếu SaveMetafilesAsPng được đặt false, Metafile nguồn sẽ được chuyển sang đồ họa vector PDF. Mỗi cách có ưu và nhược điểm. Ví dụ, nếu Metafile được chuyển sang PNG, có thể xảy ra mất chất lượng khi tài liệu kết quả được phóng to. Nếu Metafile được chuyển sang đồ họa vector PDF, có thể gặp vấn đề hiệu năng khi xem PDF.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Trả về hoặc đặt một giá trị xác định độ phân giải của các ảnh trong tài liệu PDF. Đọc/ghi float.

Giá trị: Ảnh hưởng của tham số này phụ thuộc vào một số yếu tố. Thuật toán cố gắng đưa ra kích thước ảnh đầu ra tốt nhất dựa trên giá trị thuộc tính, kích thước ảnh nguồn và kích thước khung ảnh. Sử dụng các giá trị thuộc tính tương tự có thể cho cùng một kết quả. Khuyến nghị sử dụng bước 16 hoặc 32 để thấy hiệu ứng rõ rệt.

--------------------

Thuộc tính ảnh hưởng đến kích thước tệp, thời gian xuất và chất lượng ảnh.

Giá trị mặc định là **96**.

**Trả về:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Trả về hoặc đặt một giá trị xác định độ phân giải của các ảnh trong tài liệu PDF. Đọc/ghi float.

Giá trị: Ảnh hưởng của tham số này phụ thuộc vào một số yếu tố. Thuật toán cố gắng đưa ra kích thước ảnh đầu ra tốt nhất dựa trên giá trị thuộc tính, kích thước ảnh nguồn và kích thước khung ảnh. Sử dụng các giá trị thuộc tính tương tự có thể cho cùng một kết quả. Khuyến nghị sử dụng bước 16 hoặc 32 để thấy hiệu ứng rõ rệt.

--------------------

Thuộc tính ảnh hưởng đến kích thước tệp, thời gian xuất và chất lượng ảnh.

Giá trị mặc định là **96**.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Đặt true để vẽ khung màu đen quanh mỗi slide. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Đặt true để vẽ khung màu đen quanh mỗi slide. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

Lấy hoặc đặt màu trong suốt của ảnh.

Giá trị: Màu trong suốt của ảnh.

**Trả về:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

Lấy hoặc đặt màu trong suốt của ảnh.

Giá trị: Màu trong suốt của ảnh.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Áp dụng màu trong suốt chỉ định cho ảnh nếu đặt true.

**Trả về:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Áp dụng màu trong suốt chỉ định cho ảnh nếu đặt true.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Đặt true để chuyển tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. Đọc/ghi boolean.

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
public final void setIncludeOleData(boolean value)
```

Đặt true để chuyển tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. Đọc/ghi boolean.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |