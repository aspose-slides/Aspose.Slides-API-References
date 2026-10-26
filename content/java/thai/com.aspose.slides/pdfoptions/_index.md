---
title: PdfOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ Pdf.
type: docs
url: /th/com.aspose.slides/pdfoptions/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)  
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ Pdf.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // สร้างตัวอย่างของคลาส PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // กำหนดคุณภาพของ Jpeg
>      pdfOptions.setJpegQuality((byte)90);
>      // กำหนดพฤติกรรมสำหรับเมตาไฟล์
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // กำหนดระดับการบีบอัดข้อความ
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
>  // สร้างตัวอย่างของคลาส Presentation ที่แสดงไฟล์ PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // สร้างตัวอย่างของคลาส PdfOptions
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
>  // สร้างตัวอย่างของอ็อบเจ็กต์ Presentation ที่แสดงไฟล์ PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // สร้างตัวอย่างของคลาส PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // กำหนดรหัสผ่าน PDF และสิทธิ์การเข้าถึง
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
>  // สร้างตัวอย่างของอ็อบเจ็กต์ Presentation ที่แสดงไฟล์งานนำเสนอ
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // กำหนดประเภทและขนาดของสไลด์
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

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | คอนสตรัคเตอร์เริ่มต้น. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของวัตถุ Ink ในเอกสารที่ส่งออก. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. |
| [getTextCompression()](#getTextCompression--) | ระบุประเภทการบีบอัดที่จะใช้กับเนื้อหาข้อความทั้งหมดในเอกสาร. |
| [setTextCompression(int value)](#setTextCompression-int-) | ระบุประเภทการบีบอัดที่จะใช้กับเนื้อหาข้อความทั้งหมดในเอกสาร. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | บ่งชี้ว่าการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนการบีบอัดค่าเริ่มต้น) สำหรับแต่ละภาพต้องเลือกโดยอัตโนมัติหรือไม่. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | บ่งชี้ว่าการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนการบีบอัดค่าเริ่มต้น) สำหรับแต่ละภาพต้องเลือกโดยอัตโนมัติหรือไม่. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | กำหนดว่า Aspose.Slides จะฝังแบบอักษรที่ใช้ทั่วไปสำหรับข้อความ ASCII (ช่วงโค้ด 33..127) หรือไม่. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | กำหนดว่า Aspose.Slides จะฝังแบบอักษรที่ใช้ทั่วไปสำหรับข้อความ ASCII (ช่วงโค้ด 33..127) หรือไม่. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | รับหรือกำหนดอาร์เรย์ของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรถือว่าเป็นแบบอักษรทั่วไป. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | รับหรือกำหนดอาร์เรย์ของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรถือว่าเป็นแบบอักษรทั่วไป. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | กำหนดว่าต้องฝังอักขระทั้งหมดของฟอนต์หรือเพียงส่วนที่ใช้. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | กำหนดว่าต้องฝังอักขระทั้งหมดของฟอนต์หรือเพียงส่วนที่ใช้. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | บ่งชี้ว่าข้อความควรแปลงเป็นภาพบิตแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับการทำเป็นตัวหนา. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | บ่งชี้ว่าข้อความควรแปลงเป็นภาพบิตแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับการทำเป็นตัวหนา. |
| [getJpegQuality()](#getJpegQuality--) | รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. |
| [getCompliance()](#getCompliance--) | ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้าง. |
| [setCompliance(int value)](#setCompliance-int-) | ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้าง. |
| [getPassword()](#getPassword--) | การตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | การตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | ประกอบด้วยชุดของแฟล็กที่ระบุว่าสิทธิ์การเข้าถึงใดควรให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | ประกอบด้วยชุดของแฟล็กที่ระบุว่าสิทธิ์การเข้าถึงใดควรให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | รับหรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | รับหรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. |
| [getImageTransparentColor()](#getImageTransparentColor--) | รับหรือกำหนดสีโปร่งแสงของภาพ. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | รับหรือกำหนดสีโปร่งแสงของภาพ. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | ใช้สีโปร่งแสงที่ระบุกับภาพหากเป็น true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | ใช้สีโปร่งแสงที่ระบุกับภาพหากเป็น true. |
| [getIncludeOleData()](#getIncludeOleData--) | True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. |

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

**คืนค่า:**
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของวัตถุ Ink ในเอกสารที่ส่งออก. เฉพาะการอ่าน [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

ระบุประเภทการบีบอัดที่จะใช้กับเนื้อหาข้อความทั้งหมดในเอกสาร. อ่าน/เขียน [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

ค่าเริ่มต้นคือ [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**คืนค่า:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

ระบุประเภทการบีบอัดที่จะใช้กับเนื้อหาข้อความทั้งหมดในเอกสาร. อ่าน/เขียน [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

ค่าเริ่มต้นคือ [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

บ่งชี้ว่าการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนการบีบอัดค่าเริ่มต้น) สำหรับแต่ละภาพต้องเลือกโดยอัตโนมัติหรือไม่. หากตั้งค่าเป็น true, สำหรับแต่ละภาพในงานนำเสนออัลกอริทึมการบีบอัดที่เหมาะสมที่สุดจะถูกเลือก, ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่ได้เล็กลง.

--------------------

การเลือกอัตราการบีบอัดภาพที่ดีที่สุดต้องใช้การคำนวณเพิ่มและใช้หน่วยความจำเพิ่ม, ตัวเลือกนี้มีค่าเริ่มต้นเป็น false.

--------------------

ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

บ่งชี้ว่าการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนการบีบอัดค่าเริ่มต้น) สำหรับแต่ละภาพต้องเลือกโดยอัตโนมัติหรือไม่. หากตั้งค่าเป็น true, สำหรับแต่ละภาพในงานนำเสนออัลกอริทึมการบีบอัดที่เหมาะสมที่สุดจะถูกเลือก, ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่ได้เล็กลง.

--------------------

การเลือกอัตราการบีบอัดภาพที่ดีที่สุดต้องใช้การคำนวณเพิ่มและใช้หน่วยความจำเพิ่ม, ตัวเลือกนี้มีค่าเริ่มต้นเป็น false.

--------------------

ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

กำหนดว่า Aspose.Slides จะฝังแบบอักษรทั่วไปสำหรับข้อความ ASCII (ช่วงโค้ด 33..127) หรือไม่. ฟอนต์สำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ. รายชื่อฟอนต์ทั่วไปรวมถึงฟอนต์พื้นฐาน 14 ของ PDF และฟอนต์เพิ่มเติมที่ผู้ใช้ระบุ. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**.

**คืนค่า:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

กำหนดว่า Aspose.Slides จะฝังแบบอักษรทั่วไปสำหรับข้อความ ASCII (ช่วงโค้ด 33..127) หรือไม่. ฟอนต์สำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ. รายชื่อฟอนต์ทั่วไปรวมถึงฟอนต์พื้นฐาน 14 ของ PDF และฟอนต์เพิ่มเติมที่ผู้ใช้ระบุ. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

รับหรือกำหนดอาร์เรย์ของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรถือว่าเป็นแบบอักษรทั่วไป. อ่าน/เขียน String[].

**คืนค่า:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

รับหรือกำหนดอาร์เรย์ของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรถือว่าเป็นแบบอักษรทั่วไป. อ่าน/เขียน String[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

กำหนดว่าต้องฝังอักขระทั้งหมดของฟอนต์หรือเพียงส่วนที่ใช้. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

กำหนดว่าต้องฝังอักขระทั้งหมดของฟอนต์หรือเพียงส่วนที่ใช้. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

บ่งชี้ว่าข้อความควรแปลงเป็นภาพบิตแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับการทำเป็นตัวหนา. วิธีนี้สามารถเพิ่มคุณภาพของข้อความใน PDF ที่ได้สำหรับฟอนต์บางตัว. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

บ่งชี้ว่าข้อความควรแปลงเป็นภาพบิตแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับการทำเป็นตัวหนา. วิธีนี้สามารถเพิ่มคุณภาพของข้อความใน PDF ที่ได้สำหรับฟอนต์บางตัว. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG.

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็น PDF. ค่าจะอยู่ระหว่าง 0 ถึง 100 โดยที่ 0 หมายถึงคุณภาพแย่ที่สุดแต่การบีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่การบีบอัดต่ำสุด.

ค่าดีฟอลท์คือ **100**.

**คืนค่า:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG.

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็น PDF. ค่าจะอยู่ระหว่าง 0 ถึง 100 โดยที่ 0 หมายถึงคุณภาพแย่ที่สุดแต่การบีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่การบีบอัดต่ำสุด.

ค่าดีฟอลท์คือ **100**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้าง. อ่าน/เขียน [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

ค่าเริ่มต้นคือ [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**คืนค่า:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้าง. อ่าน/เขียน [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

ค่าเริ่มต้นคือ [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

การตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

การตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

ประกอบด้วยชุดของแฟล็กที่ระบุว่าสิทธิ์การเข้าถึงใดควรให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้. ดู [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**คืนค่า:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

ประกอบด้วยชุดของแฟล็กที่ระบุว่าสิทธิ์การเข้าถึงใดควรให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้. ดู [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**. เอกสาร PDF สามารถมีกราฟิกเวกเตอร์และภาพเรสเตอร์ได้. หาก SaveMetafilesAsPng ถูกตั้งค่าเป็น true เมตาไฟล์ต้นฉบับจะถูกแปลงเป็นรูปแบบ Png และบันทึกเป็นภาพเรสเตอร์ใน PDF. หากตั้งค่าเป็น false เมตาไฟล์จะถูกแปลงเป็นกราฟิกเวกเตอร์ของ PDF. แต่ละวิธีมีข้อดีและข้อเสีย. ตัวอย่างเช่น หากเมตาไฟล์แปลงเป็น PNG อาจสูญเสียคุณภาพระหว่างการสเกลเอกสารผลลัพธ์. หากแปลงเป็นกราฟิกเวกเตอร์ของ PDF อาจพบปัญหาประสิทธิภาพในเครื่องมือดู PDF.

**คืนค่า:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**. เอกสาร PDF สามารถมีกราฟิกเวกเตอร์และภาพเรสเตอร์ได้. หาก SaveMetafilesAsPng ถูกตั้งค่าเป็น true เมตาไฟล์ต้นฉบับจะถูกแปลงเป็นรูปแบบ Png และบันทึกเป็นภาพเรสเตอร์ใน PDF. หากตั้งค่าเป็น false เมตาไฟล์จะถูกแปลงเป็นกราฟิกเวกเตอร์ของ PDF. แต่ละวิธีมีข้อดีและข้อเสีย. ตัวอย่างเช่น หากเมตาไฟล์แปลงเป็น PNG อาจสูญเสียคุณภาพระหว่างการสเกลเอกสารผลลัพธ์. หากแปลงเป็นกราฟิกเวกเตอร์ของ PDF อาจพบปัญหาประสิทธิภาพในเครื่องมือดู PDF.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

รับหรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. อ่าน/เขียน float.

ค่า: ผลของพารามิเตอร์นี้ขึ้นอยู่กับหลายปัจจัย. อัลกอริทึมพยายามหาขนาดภาพผลลัพธ์ที่ดีที่สุดตามค่าคุณสมบัตินี้, ขนาดภาพต้นฉบับและขนาดกรอบภาพ. การใช้ค่าที่คล้ายกันอาจให้ผลลัพธ์เดียวกัน. แนะนำให้ใช้ขั้นตอน 16 หรือ 32 เพื่อเห็นผลชัดเจน.

--------------------

คุณสมบัตินี้มีผลต่อขนาดไฟล์, เวลาในการส่งออกและคุณภาพของภาพ.

ค่าดีฟอลท์คือ **96**.

**คืนค่า:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

รับหรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. อ่าน/เขียน float.

ค่า: ผลของพารามิเตอร์นี้ขึ้นอยู่กับหลายปัจจัย. อัลกอริทึมพยายามหาขนาดภาพผลลัพธ์ที่ดีที่สุดตามค่าคุณสมบัตินี้, ขนาดภาพต้นฉบับและขนาดกรอบภาพ. การใช้ค่าที่คล้ายกันอาจให้ผลลัพธ์เดียวกัน. แนะนำให้ใช้ขั้นตอน 16 หรือ 32 เพื่อเห็นผลชัดเจน.

--------------------

คุณสมบัตินี้มีผลต่อขนาดไฟล์, เวลาในการส่งออกและคุณภาพของภาพ.

ค่าดีฟอลท์คือ **96**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

รับหรือกำหนดสีโปร่งแสงของภาพ.

ค่า: สีของภาพที่โปร่งแสง.

**คืนค่า:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

รับหรือกำหนดสีโปร่งแสงของภาพ.

ค่า: สีของภาพที่โปร่งแสง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

ใช้สีโปร่งแสงที่ระบุกับภาพหากเป็น true.

**คืนค่า:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

ใช้สีโปร่งแสงที่ระบุกับภาพหากเป็น true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. อ่าน/เขียน boolean.

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

**คืนค่า:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. อ่าน/เขียน boolean.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |