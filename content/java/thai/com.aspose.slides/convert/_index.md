---
title: Convert
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: แสดงถึงกลุ่มของเมธอดที่มีจุดประสงค์เพื่อแปลง .
type: docs
url: /th/com.aspose.slides/convert/
---
**สืบทอด:**
java.lang.Object
```
public class Convert
```

แสดงถึงกลุ่มของเมธอดที่มีจุดประสงค์เพื่อแปลง [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Convert()](#Convert--) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | แปลง [Presentation](../../com.aspose.slides/presentation) โดยใช้ส่วนต่อท้ายของเส้นทางเอาต์พุตที่ส่งมาเพื่อกำหนดรูปแบบการส่งออกที่ต้องการ. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | แปลง [Presentation](../../com.aspose.slides/presentation) เป็น PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | แปลง [Presentation](../../com.aspose.slides/presentation) เป็น PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | แปลง [Presentation](../../com.aspose.slides/presentation) เป็น PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | แปลง [Presentation](../../com.aspose.slides/presentation) เป็น PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | แปลง [Presentation](../../com.aspose.slides/presentation) เป็น SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | แปลง [Presentation](../../com.aspose.slides/presentation) เป็น SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | แปลง [Presentation](../../com.aspose.slides/presentation) เป็น SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | แปลง [Presentation](../../com.aspose.slides/presentation) เป็น SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | แปลง [Presentation](../../com.aspose.slides/presentation) เป็น SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ PNG. |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | แปลงการนำเสนออินพุตเป็นรูปแบบ TIFF พร้อมตัวเลือกกำหนดเอง. |

### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) โดยใช้ส่วนต่อท้ายของเส้นทางเอาต์พุตที่ส่งมาเพื่อกำหนดรูปแบบการส่งออกที่ต้องการ.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presPath | java.lang.String | เส้นทางของการนำเสนออินพุต |
| outPath | java.lang.String | เส้นทางเอาต์พุต |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) เป็น PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presPath | java.lang.String | เส้นทางของการนำเสนออินพุต |
| outPath | java.lang.String | เส้นทางเอาต์พุต |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

แปลง [Presentation](../../com.aspose.slides/presentation) เป็น PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presPath | java.lang.String | เส้นทางของการนำเสนออินพุต |
| outPath | java.lang.String | เส้นทางเอาต์พุต |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | ตัวเลือกการส่งออก PDF |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) เป็น PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| outPath | java.lang.String | เส้นทางเอาต์พุต |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

แปลง [Presentation](../../com.aspose.slides/presentation) เป็น PDF.

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| outPath | java.lang.String | เส้นทางเอาต์พุต |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | ตัวเลือกการส่งออก PDF |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) เป็น SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presPath | java.lang.String | เส้นทางของการนำเสนออินพุต |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) เป็น SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presPath | java.lang.String | เส้นทางของการนำเสนออินพุต |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | คอลแบ็กที่คืนค่าเส้นทางเอาต์พุต SVG สำหรับแต่ละสไลด์ในงานนำเสนอ |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) เป็น SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | คอลแบ็กที่คืนค่าเส้นทางเอาต์พุต SVG สำหรับแต่ละสไลด์ในงานนำเสนอ |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

แปลง [Presentation](../../com.aspose.slides/presentation) เป็น SVG.

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | ตัวเลือกการส่งออก SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

แปลง [Presentation](../../com.aspose.slides/presentation) เป็น SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index), svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | คอลแบ็กที่คืนค่าเส้นทางเอาต์พุต SVG สำหรับแต่ละสไลด์ในงานนำเสนอ |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | ตัวเลือกการส่งออก SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ JPEG. หากชื่อไฟล์เอาต์พุตระบุเป็น "myPath/myFilename.jpeg", ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.jpeg" ที่ N คือหมายเลขสไลด์.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```

แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ JPEG. หากชื่อไฟล์เอาต์พุตระบุเป็น "myPath/myFilename.jpeg", ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.jpeg" ที่ N คือหมายเลขสไลด์.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |
| imageSize | java.awt.Dimension | ขนาดของแต่ละภาพที่สร้างขึ้น. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ JPEG. หากชื่อไฟล์เอาต์พุตระบุเป็น "myPath/myFilename.jpeg", ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.jpeg" ที่ N คือหมายเลขสไลด์.

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |
| scale | float | ปัจจัยการขยายที่ใช้กับภาพเอาต์พุตเทียบกับขนาดสไลด์ต้นฉบับ. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ PNG. หากชื่อไฟล์เอาต์พุตระบุเป็น "myPath/myFilename.png", ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.png" ที่ N คือหมายเลขสไลด์.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```

แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ PNG. หากชื่อไฟล์เอาต์พุตระบุเป็น "myPath/myFilename.png", ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.png" ที่ N คือหมายเลขสไลด์.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |
| imageSize | java.awt.Dimension | ขนาดของแต่ละภาพที่สร้างขึ้น. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ PNG. หากชื่อไฟล์เอาต์พุตระบุเป็น "myPath/myFilename.png", ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.png" ที่ N คือหมายเลขสไลด์.

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |
| scale | float | ปัจจัยการขยายที่ใช้กับภาพเอาต์พุตเทียบกับขนาดสไลด์ต้นฉบับ. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

แปลงการนำเสนออินพุตเป็นชุดของภาพในรูปแบบ TIFF. หากชื่อไฟล์เอาต์พุตระบุเป็น "myPath/myFilename.tiff", ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.tiff" ที่ N คือหมายเลขสไลด์.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

แปลงการนำเสนออินพุตเป็นรูปแบบ TIFF พร้อมตัวเลือกกำหนดเอง. หากชื่อไฟล์เอาต์พุตระบุเป็น "myPath/myFilename.tiff" และ multipage เป็น false, ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.tiff" ที่ N คือหมายเลขสไลด์. หาก multipage เป็น true, ผลลัพธ์จะเป็นเอกสารหลายหน้า "myPath/myFilename.tiff".

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | ตัวเลือกการบันทึก TIFF. |
| multipage | boolean | ระบุว่าควรสร้างเอกสาร TIFF หลายหน้าหรือไม่. |