---
title: PdfOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API อ้างอิง
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ Pdf.
type: docs
url: /th/com.aspose.slides/pdfoptions/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)  
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ Pdf.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // สร้างอินสแตนซ์ของคลาส PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // ตั้งค่าคุณภาพของ Jpeg
>      pdfOptions.setJpegQuality((byte)90);
>      // ตั้งค่าพฤติกรรมสำหรับเมตาไฟล์
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // ตั้งค่าระดับการบีบอัดข้อความ
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // กำหนดมาตรฐาน PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // บันทึกการนำเสนอเป็น PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์ PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // สร้างอินสแตนซ์ของคลาส PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // เพิ่มสไลด์ที่ซ่อนอยู่
>      pdfOptions.setShowHiddenSlides(true);
>      // บันทึกการนำเสนอเป็น PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // สร้างอินสแตนซ์ของอ็อบเจ็กต์ Presentation ที่แทนไฟล์ PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // สร้างอินสแตนซ์ของคลาส PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // ตั้งค่ารหัสผ่าน PDF และการอนุญาตการเข้าถึง
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // บันทึกการนำเสนอเป็น PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // สร้างอินสแตนซ์ของอ็อบเจ็กต์ Presentation ที่แทนไฟล์การนำเสนอ
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // ตั้งค่าประเภทและขนาดสไลด์
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
## ตัวสร้าง

| Constructor | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | คอนสตรัคเตอร์เริ่มต้น. |
## เมธอด

| Method | Description |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ |
| [getTextCompression()](#getTextCompression--) | ระบุประเภทการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร. |
| [setTextCompression(int value)](#setTextCompression-int-) | ระบุประเภทการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | ระบุว่าการบีบอัดที่มีประสิทธิภาพที่สุด (แทนค่าปริยาย) สำหรับแต่ละภาพควรถูกเลือกโดยอัตโนมัติหรือไม่. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | ระบุว่าการบีบอัดที่มีประสิทธิภาพที่สุด (แทนค่าปริยาย) สำหรับแต่ละภาพควรถูกเลือกโดยอัตโนมัติหรือไม่. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | กำหนดว่า Aspose.Slides จะฝังแบบอักษรทั่วไปสำหรับข้อความ ASCII (รหัส 33..127) หรือไม่. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | กำหนดว่า Aspose.Slides จะฝังแบบอักษรทั่วไปสำหรับข้อความ ASCII (รหัส 33..127) หรือไม่. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | รับหรือกำหนดอาเรย์ของชื่อฟอนต์ที่กำหนดโดยผู้ใช้ซึ่ง Aspose.Slides ควรถือเป็นฟอนต์ทั่วไป. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | รับหรือกำหนดอาเรย์ของชื่อฟอนต์ที่กำหนดโดยผู้ใช้ซึ่ง Aspose.Slides ควรถือเป็นฟอนต์ทั่วไป. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | กำหนดว่าตัวอักษรทั้งหมดของฟอนต์จะถูกฝังหรือเฉพาะส่วนที่ใช้. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | กำหนดว่าตัวอักษรทั้งหมดของฟอนต์จะถูกฝังหรือเฉพาะส่วนที่ใช้. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | ระบุว่าข้อความควรถูกแปลงเป็นบิทแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับการจัดรูปแบบตัวหนา. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | ระบุว่าข้อความควรถูกแปลงเป็นบิทแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับการจัดรูปแบบตัวหนา. |
| [getJpegQuality()](#getJpegQuality--) | รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. |
| [getCompliance()](#getCompliance--) | ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้างขึ้น. |
| [setCompliance(int value)](#setCompliance-int-) | ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้างขึ้น. |
| [getPassword()](#getPassword--) | ตั้งค่ารหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | ตั้งค่ารหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | บรรจุชุดของแฟล็กที่ระบุว่าการอนุญาตการเข้าถึงใดควรได้รับเมื่อเอกสารถูกเปิดด้วยสิทธิ์ผู้ใช้. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | บรรจุชุดของแฟล็กที่ระบุว่าการอนุญาตการเข้าถึงใดควรได้รับเมื่อเอกสารถูกเปิดด้วยสิทธิ์ผู้ใช้. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | ตั้งค่าเป็น true เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | ตั้งค่าเป็น true เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | รับหรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | รับหรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | ตั้งค่าเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | ตั้งค่าเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. |
| [getImageTransparentColor()](#getImageTransparentColor--) | รับหรือกำหนดสีใสของภาพ. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | รับหรือกำหนดสีใสของภาพ. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | นำสีใสที่ระบุไปใช้กับภาพหากเป็น true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | นำสีใสที่ระบุไปใช้กับภาพหากเป็น true. |
| [getIncludeOleData()](#getIncludeOleData--) | ตั้งค่าเป็น true เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | ตั้งค่าเป็น true เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

คอนสตรัคเตอร์เริ่มต้น.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**ผลลัพธ์:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก. อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**ผลลัพธ์:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ false.

**ผลลัพธ์:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

ระบุประเภทการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร. อ่าน/เขียน [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

ค่าเริ่มต้นคือ [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**ผลลัพธ์:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

ระบุประเภทการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร. อ่าน/เขียน [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

ค่าเริ่มต้นคือ [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

ระบุว่าการบีบอัดที่มีประสิทธิภาพที่สุด (แทนค่าปริยาย) สำหรับแต่ละภาพควรถูกเลือกโดยอัตโนมัติหรือไม่. หากตั้งค่าเป็น true, สำหรับแต่ละภาพในงานนำเสนออัลกอริทึมบีบอัดที่เหมาะสมที่สุดจะถูกเลือก, ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่ได้มีขนาดเล็กลง.

--------------------

การเลือกอัตราการบีบอัดภาพที่ดีที่สุดใช้การประมวลผลมากและใช้ RAM เพิ่มเติม, และตัวเลือกนี้มีค่าเริ่มต้นเป็น false.

--------------------

ค่าเริ่มต้นคือ false.

**ผลลัพธ์:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

ระบุว่าการบีบอัดที่มีประสิทธิภาพที่สุด (แทนค่าปริยาย) สำหรับแต่ละภาพควรถูกเลือกโดยอัตโนมัติหรือไม่. หากตั้งค่าเป็น true, สำหรับแต่ละภาพในงานนำเสนออัลกอริทึมบีบอัดที่เหมาะสมที่สุดจะถูกเลือก, ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่ได้มีขนาดเล็กลง.

--------------------

การเลือกอัตราการบีบอัดภาพที่ดีที่สุดใช้การประมวลผลมากและใช้ RAM เพิ่มเติม, และตัวเลือกนี้มีค่าเริ่มต้นเป็น false.

--------------------

ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

กำหนดว่า Aspose.Slides จะฝังฟอนต์ทั่วไปสำหรับข้อความ ASCII (ช่วงรหัส 33..127) หรือไม่. ฟอนต์สำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ. รายการฟอนต์ทั่วไปรวมถึงฟอนต์พื้นฐาน 14 ตัวของ PDF และฟอนต์เพิ่มเติมที่ผู้ใช้ระบุ. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**.

**ผลลัพธ์:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

กำหนดว่า Aspose.Slides จะฝังฟอนต์ทั่วไปสำหรับข้อความ ASCII (ช่วงรหัส 33..127) หรือไม่. ฟอนต์สำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ. รายการฟอนต์ทั่วไปรวมถึงฟอนต์พื้นฐาน 14 ตัวของ PDF และฟอนต์เพิ่มเติมที่ผู้ใช้ระบุ. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

รับหรือกำหนดอาเรย์ของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรถือเป็นฟอนต์ทั่วไป. อ่าน/เขียน String[].

**ผลลัพธ์:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

รับหรือกำหนดอาเรย์ของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรถือเป็นฟอนต์ทั่วไป. อ่าน/เขียน String[].

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

กำหนดว่าตัวอักษรทั้งหมดของฟอนต์จะถูกฝังหรือเฉพาะส่วนที่ใช้. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**ผลลัพธ์:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

กำหนดว่าตัวอักษรทั้งหมดของฟอนต์จะถูกฝังหรือเฉพาะส่วนที่ใช้. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

ระบุว่าข้อความควรถูกแปลงเป็นบิทแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับการจัดรูปแบบตัวหนา. วิธีนี้สามารถเพิ่มคุณภาพของข้อความใน PDF ที่ได้สำหรับฟอนต์บางประเภท. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**ผลลัพธ์:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

ระบุว่าข้อความควรถูกแปลงเป็นบิทแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับการจัดรูปแบบตัวหนา. วิธีนี้สามารถเพิ่มคุณภาพของข้อความใน PDF ที่ได้สำหรับฟอนต์บางประเภท. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG.

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็น PDF. ค่าที่เป็นไปได้ตั้งแต่ 0 ถึง 100 โดย 0 หมายถึงคุณภาพแย่ที่สุดแต่การบีบอัดสูงสุด และ 100 หมายถึงคุณภาพดีที่สุดแต่การบีบอัดต่ำสุด.

ค่าเริ่มต้นคือ **100**.

**ผลลัพธ์:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG.

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็น PDF. ค่าที่เป็นไปได้ตั้งแต่ 0 ถึง 100 โดย 0 หมายถึงคุณภาพแย่ที่สุดแต่การบีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่การบีบอัดต่ำสุด.

ค่าเริ่มต้นคือ **100**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้างขึ้น. อ่าน/เขียน [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

ค่าเริ่มต้นคือ [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**ผลลัพธ์:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้างขึ้น. อ่าน/เขียน [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

ค่าเริ่มต้นคือ [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

ตั้งค่ารหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

ตั้งค่ารหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

บรรจุชุดของแฟล็กที่ระบุว่าการอนุญาตการเข้าถึงใดควรได้รับเมื่อเอกสารถูกเปิดด้วยสิทธิ์ผู้ใช้. ดู [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**ผลลัพธ์:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

บรรจุชุดของแฟล็กที่ระบุว่าการอนุญาตการเข้าถึงใดควรได้รับเมื่อเอกสารถูกเปิดด้วยสิทธิ์ผู้ใช้. ดู [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

ตั้งค่าเป็น true เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**. เอกสาร PDF สามารถมีกราฟิกเวกเตอร์และภาพเรสเตอร์ได้. หาก SaveMetafilesAsPng ตั้งเป็น true เมตาไฟล์ต้นฉบับจะถูกแปลงเป็นรูปแบบ Png และบันทึกเป็น PDF เป็นภาพเรสเตอร์. หากตั้งเป็น false เมตาไฟล์ต้นฉบับจะถูกแปลงเป็นกราฟิกเวกเตอร์ของ PDF. วิธีการแต่ละแบบมีข้อดีและข้อเสีย. ตัวอย่างเช่น หากเมตาไฟล์ถูกแปลงเป็น PNG อาจสูญเสียคุณภาพบางส่วนระหว่างการสเกลเอกสารที่ได้. หากแปลงเป็นกราฟิกเวกเตอร์ของ PDF อาจเกิดปัญหาประสิทธิภาพในโปรแกรมดู PDF.

**ผลลัพธ์:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

ตั้งค่าเป็น true เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**. เอกสาร PDF สามารถมีกราฟิกเวกเตอร์และภาพเรสเตอร์ได้. หาก SaveMetafilesAsPng ตั้งเป็น true เมตาไฟล์ต้นฉบับจะถูกแปลงเป็นรูปแบบ Png และบันทึกเป็น PDF เป็นภาพเรสเตอร์. หากตั้งเป็น false เมตาไฟล์ต้นฉบับจะถูกแปลงเป็นกราฟิกเวกเตอร์ของ PDF. วิธีการแต่ละแบบมีข้อดีและข้อเสีย. ตัวอย่างเช่น หากเมตาไฟล์ถูกแปลงเป็น PNG อาจสูญเสียคุณภาพบางส่วนระหว่างการสเกลเอกสารที่ได้. หากแปลงเป็นกราฟิกเวกเตอร์ของ PDF อาจเกิดปัญหาประสิทธิภาพในโปรแกรมดู PDF.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

รับหรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. อ่าน/เขียน float.

Value: ผลของพารามิเตอร์นี้ขึ้นอยู่กับหลายปัจจัย. อัลกอริทึมพยายามหา ขนาดภาพผลลัพธ์ที่ดีที่สุดตามค่าคุณสมบัติ, ขนาดภาพต้นฉบับและขนาดกรอบภาพ. การใช้ค่าที่คล้ายกันอาจให้ผลลัพธ์เดียวกัน. แนะนำให้ใช้ขั้น 16 หรือ 32 เพื่อให้เห็นผล.

--------------------

คุณสมบัตินี้มีผลต่อขนาดไฟล์, เวลาในการส่งออกและคุณภาพของภาพ.

ค่าเริ่มต้นคือ **96**.

**ผลลัพธ์:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

รับหรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. อ่าน/เขียน float.

Value: ผลของพารามิเตอร์นี้ขึ้นอยู่กับหลายปัจจัย. อัลกอริทึมพยายามหา ขนาดภาพผลลัพธ์ที่ดีที่สุดตามค่าคุณสมบัติ, ขนาดภาพต้นฉบับและขนาดกรอบภาพ. การใช้ค่าที่คล้ายกันอาจให้ผลลัพธ์เดียวกัน. แนะนำให้ใช้ขั้น 16 หรือ 32 เพื่อให้เห็นผล.

--------------------

คุณสมบัตินี้มีผลต่อขนาดไฟล์, เวลาในการส่งออกและคุณภาพของภาพ.

ค่าเริ่มต้นคือ **96**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

ตั้งค่าเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**ผลลัพธ์:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

ตั้งค่าเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

รับหรือกำหนดสีใสของภาพ.

Value: สีของภาพที่เป็นแบบใส.

**ผลลัพธ์:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

รับหรือกำหนดสีใสของภาพ.

Value: สีของภาพที่เป็นแบบใส.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

นำสีใสที่ระบุไปใช้กับภาพหากเป็น true.

**ผลลัพธ์:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

นำสีใสที่ระบุไปใช้กับภาพหากเป็น true.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

ตั้งค่าเป็น true เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. อ่าน/เขียน  boolean .

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

ค่าเริ่มต้นคือ **false** .

**ผลลัพธ์:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

ตั้งค่าเป็น true เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. อ่าน/เขียน  boolean .

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

ค่าเริ่มต้นคือ **false** .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |