---
title: Convert
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho một nhóm các phương thức nhằm chuyển đổi .
type: docs
url: /vi/com.aspose.slides/convert/
---
**Kế thừa:**
java.lang.Object
```
public class Convert
```

Đại diện cho một nhóm các phương thức nhằm chuyển đổi [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Hàm tạo

| Constructor | Mô tả |
| --- | --- |
| [Convert()](#Convert--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sử dụng phần mở rộng đường dẫn đầu ra được truyền vào để xác định định dạng xuất cần thiết. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng PNG. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Chuyển đổi bài thuyết trình đầu vào sang định dạng TIFF với các tùy chọn tùy chỉnh. |
### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sử dụng phần mở rộng đường dẫn đầu ra được truyền vào để xác định định dạng xuất cần thiết.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presPath | java.lang.String | Đường dẫn của bài thuyết trình đầu vào |
| outPath | java.lang.String | Đường dẫn đầu ra |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presPath | java.lang.String | Đường dẫn của bài thuyết trình đầu vào |
| outPath | java.lang.String | Đường dẫn đầu ra |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presPath | java.lang.String | Đường dẫn của bài thuyết trình đầu vào |
| outPath | java.lang.String | Đường dẫn đầu ra |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Các tùy chọn PDF đầu ra |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào |
| outPath | java.lang.String | Đường dẫn đầu ra |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.setCompliance(PdfCompliance.PdfUa);
>      Convert.toPdf(pres, "output.pdf", pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào |
| outPath | java.lang.String | Đường dẫn đầu ra |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Các tùy chọn PDF đầu ra |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presPath | java.lang.String | Đường dẫn của bài thuyết trình đầu vào |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presPath | java.lang.String | Đường dẫn của bài thuyết trình đầu vào |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Hàm gọi ngược trả về đường dẫn SVG đầu ra cho mỗi slide trong bài thuyết trình |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, new Convert.GetOutPathCallback() {
>          public String invoke(Slide slide, int index) {
>              return String.format("pres_%d-out.svg", index);
>          }
>      });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Hàm gọi ngược trả về đường dẫn SVG đầu ra cho mỗi slide trong bài thuyết trình |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Các tùy chọn xuất SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

Chuyển đổi [Presentation](../../com.aspose.slides/presentation) sang SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, new Convert.GetOutPathCallback() {
>          public String invoke(Slide slide, int index) {
>              return String.format("pres_%d-out.svg", index);
>          }
>      }, svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Hàm gọi ngược trả về đường dẫn SVG đầu ra cho mỗi slide trong bài thuyết trình |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Các tùy chọn xuất SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng JPEG. Nếu tên tệp đầu ra được cung cấp dưới dạng "myPath/myFilename.jpeg", kết quả sẽ được lưu dưới dạng một tập hợp các tệp "myPath/myFilename_N.jpeg", trong đó N là số slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào. |
| outputFileName | java.lang.String | Tên tệp đầu ra. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng JPEG. Nếu tên tệp đầu ra được cung cấp dưới dạng "myPath/myFilename.jpeg", kết quả sẽ được lưu dưới dạng một tập hợp các tệp "myPath/myFilename_N.jpeg", trong đó N là số slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào |
| outputFileName | java.lang.String | Tên tệp đầu ra. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Kích thước của mỗi hình ảnh được tạo. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng JPEG. Nếu tên tệp đầu ra được cung cấp dưới dạng "myPath/myFilename.jpeg", kết quả sẽ được lưu dưới dạng một tập hợp các tệp "myPath/myFilename_N.jpeg", trong đó N là số slide.

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào. |
| outputFileName | java.lang.String | Tên tệp đầu ra. |
| scale | float | Hệ số tỷ lệ được áp dụng cho các hình ảnh đầu ra so với kích thước slide gốc. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Các tùy chọn render. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng PNG. Nếu tên tệp đầu ra được cung cấp dưới dạng "myPath/myFilename.png", kết quả sẽ được lưu dưới dạng một tập hợp các tệp "myPath/myFilename_N.png", trong đó N là số slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào. |
| outputFileName | java.lang.String | Tên tệp đầu ra. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng PNG. Nếu tên tệp đầu ra được cung cấp dưới dạng "myPath/myFilename.png", kết quả sẽ được lưu dưới dạng một tập hợp các tệp "myPath/myFilename_N.png", trong đó N là số slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào |
| outputFileName | java.lang.String | Tên tệp đầu ra. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Kích thước của mỗi hình ảnh được tạo. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng PNG. Nếu tên tệp đầu ra được cung cấp dưới dạng "myPath/myFilename.png", kết quả sẽ được lưu dưới dạng một tập hợp các tệp "myPath/myFilename_N.png", trong đó N là số slide.

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào. |
| outputFileName | java.lang.String | Tên tệp đầu ra. |
| scale | float | Hệ số tỷ lệ được áp dụng cho các hình ảnh đầu ra so với kích thước slide gốc. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Các tùy chọn render. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

Chuyển đổi bài thuyết trình đầu vào thành một tập hợp các hình ảnh định dạng TIFF. Nếu tên tệp đầu ra được cung cấp dưới dạng "myPath/myFilename.tiff", kết quả sẽ được lưu dưới dạng một tập hợp các tệp "myPath/myFilename_N.tiff", trong đó N là số slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào. |
| outputFileName | java.lang.String | Tên tệp đầu ra. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipcape)
```

Chuyển đổi bài thuyết trình đầu vào sang định dạng TIFF với các tùy chọn tùy chỉnh. Nếu tên tệp đầu ra được cung cấp dưới dạng "myPath/myFilename.tiff" và multipage là false, kết quả sẽ được lưu dưới dạng một tập hợp các tệp "myPath/myFilename_N.tiff", trong đó N là số slide. Ngược lại, nếu multipage là true, kết quả sẽ là một tài liệu đa trang "myPath/myFilename.tiff".

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  ITiffOptions options = new TiffOptions();
>  options.setCompressionType(TiffCompressionTypes.CCITT3);
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "pres.tiff", options, false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bài thuyết trình đầu vào. |
| outputFileName | java.lang.String | Tên tệp đầu ra. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Các tùy chọn lưu TIFF. |
| multipage | boolean | Xác định liệu tài liệu TIFF được tạo có phải là đa trang hay không. |