---
title: Convert
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แทนกลุ่มของเมธอดที่ออกแบบมาเพื่อแปลง.
type: docs
url: /th/com.aspose.slides/convert/
---
**การสืบทอด:**  
java.lang.Object  
```
public class Convert
```

แทนกลุ่มของเมธอดที่ออกแบบมาเพื่อแปลง [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [Convert()](#Convert--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | แปลง [Presentation](../../com.aspose.slides/presentation) โดยใช้ส่วนขยายของเส้นทางเอาต์พุตที่ส่งเข้ามาเพื่อกำหนดรูปแบบการส่งออกที่ต้องการ. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ PNG. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | แปลงการนำเสนออินพุตเป็นรูปแบบ TIFF พร้อมตัวเลือกที่กำหนดเอง. |

### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) โดยใช้ส่วนขยายของเส้นทางเอาต์พุตที่ส่งเข้ามาเพื่อกำหนดรูปแบบการส่งออกที่ต้องการ.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| presPath | java.lang.String | เส้นทางของการนำเสนออินพุต |
| outPath | java.lang.String | เส้นทางเอาต์พุต |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| presPath | java.lang.String | เส้นทางของการนำเสนออินพุต |
| outPath | java.lang.String | เส้นทางเอาต์พุต |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| presPath | java.lang.String | เส้นทางของการนำเสนออินพุต |
| outPath | java.lang.String | เส้นทางเอาต์พุต |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | ตัวเลือก PDF ขาออก |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น PDF.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| outPath | java.lang.String | เส้นทางเอาต์พุต |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น PDF.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| outPath | java.lang.String | เส้นทางเอาต์พุต |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | ตัวเลือก PDF ขาออก |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| presPath | java.lang.String | เส้นทางของการนำเสนออินพุต |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| presPath | java.lang.String | เส้นทางของการนำเสนออินพุต |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | คอลแบ็กที่คืนค่าเส้นทางเอาต์พุต SVG สำหรับแต่ละสไลด์ในงานนำเสนอ |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น SVG.

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

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | คอลแบ็กที่คืนค่าเส้นทางเอาต์พุต SVG สำหรับแต่ละสไลด์ในงานนำเสนอ |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น SVG.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | ตัวเลือกการส่งออก SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

แปลง [Presentation](../../com.aspose.slides/presentation) ไปเป็น SVG.

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

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | คอลแบ็กที่คืนค่าเส้นทางเอาต์พุต SVG สำหรับแต่ละสไลด์ในงานนำเสนอ |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | ตัวเลือกการส่งออก SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ JPEG. หากชื่อไฟล์เอาต์พุตกำหนดเป็น "myPath/myFilename.jpeg" ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename\_N.jpeg" โดยที่ N คือหมายเลขสไลด์.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ JPEG. หากชื่อไฟล์เอาต์พุตกำหนดเป็น "myPath/myFilename.jpeg" ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename\_N.jpeg" โดยที่ N คือหมายเลขสไลด์.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |
| imageSize | [Size](../../com.aspose.slides.android/size) | ขนาดของแต่ละภาพที่สร้าง. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ JPEG. หากชื่อไฟล์เอาต์พุตกำหนดเป็น "myPath/myFilename.jpeg" ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename\_N.jpeg" โดยที่ N คือหมายเลขสไลด์.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |
| scale | float | อัตราส่วนการปรับขนาดที่ใช้กับภาพเอาต์พุตเทียบกับขนาดสไลด์ต้นฉบับ. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ PNG. หากชื่อไฟล์เอาต์พุตกำหนดเป็น "myPath/myFilename.png" ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename\_N.png" โดยที่ N คือหมายเลขสไลด์.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ PNG. หากชื่อไฟล์เอาต์พุตกำหนดเป็น "myPath/myFilename.png" ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename\_N.png" โดยที่ N คือหมายเลขสไลด์.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |
| imageSize | [Size](../../com.aspose.slides.android/size) | ขนาดของแต่ละภาพที่สร้าง. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ PNG. หากชื่อไฟล์เอาต์พุตกำหนดเป็น "myPath/myFilename.png" ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename\_N.png" โดยที่ N คือหมายเลขสไลด์.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |
| scale | float | อัตราส่วนการปรับขนาดที่ใช้กับภาพเอาต์พุตเทียบกับขนาดสไลด์ต้นฉบับ. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | ตัวเลือกการเรนเดอร์. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

แปลงการนำเสนออินพุตเป็นชุดของรูปภาพรูปแบบ TIFF. หากชื่อไฟล์เอาต์พุตกำหนดเป็น "myPath/myFilename.tiff" ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename\_N.tiff" โดยที่ N คือหมายเลขสไลด์.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

แปลงการนำเสนออินพุตเป็นรูปแบบ TIFF พร้อมตัวเลือกที่กำหนดเอง. หากชื่อไฟล์เอาต์พุตเป็น "myPath/myFilename.tiff" และ multipage เป็น false ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename\_N.tiff" โดยที่ N คือหมายเลขสไลด์. หาก multipage เป็น true ผลลัพธ์จะเป็นเอกสารหลายหน้า "myPath/myFilename.tiff".

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนออินพุต. |
| outputFileName | java.lang.String | ชื่อไฟล์เอาต์พุต. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | ตัวเลือกการบันทึก TIFF. |
| multipage | boolean | ระบุว่าจะให้เอกสาร TIFF ที่สร้างเป็นหลายหน้า หรือไม่. |