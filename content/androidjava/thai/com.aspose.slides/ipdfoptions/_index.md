---
title: IPdfOptions
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ Pdf.
type: docs
url: /th/com.aspose.slides/ipdfoptions/
---
**ทั้งหมดที่ทำตามอินเทอร์เฟซ:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ Pdf.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | ระบุประเภทของการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร. |
| [setTextCompression(int value)](#setTextCompression-int-) | ระบุประเภทของการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | ระบุว่าการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนการบีบอัดเริ่มต้น) สำหรับแต่ละรูปภาพต้องถูกเลือกโดยอัตโนมัติหรือไม่. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | ระบุว่าการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนการบีบอัดเริ่มต้น) สำหรับแต่ละรูปภาพต้องถูกเลือกโดยอัตโนมัติหรือไม่. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True เพื่อฝังแบบอักษร true type สำหรับอักขระ ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True เพื่อฝังแบบอักษร true type สำหรับอักขระ ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | คืนค่า หรือกำหนดอาร์เรย์ของชื่อฟอนท์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรพิจารณาว่าเป็นทั่วไป. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | กำหนดว่าควรฝังอักขระทั้งหมดของแบบอักษรหรือเพียงส่วนที่ใช้. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | กำหนดว่าควรฝังอักขระทั้งหมดของแบบอักษรหรือเพียงส่วนที่ใช้. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | ระบุว่าข้อความควรถูกแปลงเป็นบิตแมพและบันทึกเป็น PDF เมื่อแบบอักษรไม่รองรับการทำตัวหนา. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | ระบุว่าข้อความควรถูกแปลงเป็นบิตแมพและบันทึกเป็น PDF เมื่อแบบอักษรไม่รองรับการทำตัวหนา. |
| [getJpegQuality()](#getJpegQuality--) | คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของรูป JPEG ภายในเอกสาร PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของรูป JPEG ภายในเอกสาร PDF. |
| [getCompliance()](#getCompliance--) | ระดับการสอดคล้องที่ต้องการสำหรับเอกสาร PDF ที่สร้าง. |
| [setCompliance(int value)](#setCompliance-int-) | ระดับการสอดคล้องที่ต้องการสำหรับเอกสาร PDF ที่สร้าง. |
| [getPassword()](#getPassword--) | การตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | การตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | ประกอบด้วยชุดของแฟล็กที่ระบุสิทธิ์การเข้าถึงที่จะให้เมื่อเปิดเอกสารด้วยการเข้าถึงของผู้ใช้. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | ประกอบด้วยชุดของแฟล็กที่ระบุสิทธิ์การเข้าถึงที่จะให้เมื่อเปิดเอกสารด้วยการเข้าถึงของผู้ใช้. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True เพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True เพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | คืนค่า หรือกำหนดค่าที่กำหนดความละเอียดของรูปภาพภายในเอกสาร PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | คืนค่า หรือกำหนดค่าที่กำหนดความละเอียดของรูปภาพภายในเอกสาร PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True เพื่อวาดกรอบสีดำรอบสไลด์แต่ละสไลด์. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True เพื่อวาดกรอบสีดำรอบสไลด์แต่ละสไลด์. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | รับหรือกำหนดสีโปร่งใสของภาพ. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | รับหรือกำหนดสีโปร่งใสของภาพ. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | นำสีโปร่งใสที่ระบุไปใช้กับภาพหากเป็น true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | นำสีโปร่งใสที่ระบุไปใช้กับภาพหากเป็น true. |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. |
| [getIncludeOleData()](#getIncludeOleData--) | True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

ระบุประเภทของการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร. อ่าน/เขียน [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

ค่าเริ่มต้นคือ [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**คืนค่า:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

ระบุประเภทของการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร. อ่าน/เขียน [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

ค่าเริ่มต้นคือ [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

ระบุว่าการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนการบีบอัดเริ่มต้น) สำหรับแต่ละรูปภาพต้องถูกเลือกโดยอัตโนมัติหรือไม่. หากตั้งค่าเป็น true, สำหรับแต่ละรูปภาพในงานนำเสนออัลกอริทึมการบีบอัดที่เหมาะสมที่สุดจะถูกเลือก, ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่ได้เล็กลง.

--------------------

การเลือกอัตราการบีบอัดภาพที่ดีที่สุดต้องใช้การคำนวณที่สูงและใช้หน่วยความจำเพิ่มเติม, ตัวเลือกนี้ตั้งค่าเป็น false โดยค่าเริ่มต้น.

--------------------

ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

ระบุว่าการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนการบีบอัดเริ่มต้น) สำหรับแต่ละรูปภาพต้องถูกเลือกโดยอัตโนมัติหรือไม่. หากตั้งค่าเป็น true, สำหรับแต่ละรูปภาพในงานนำเสนออัลกอริทึมการบีบอัดที่เหมาะสมที่สุดจะถูกเลือก, ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่ได้เล็กลง.

--------------------

การเลือกอัตราการบีบอัดภาพที่ดีที่สุดต้องใช้การคำนวณที่สูงและใช้หน่วยความจำเพิ่มเติม, ตัวเลือกนี้ตั้งค่าเป็น false โดยค่าเริ่มต้น.

--------------------

ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True เพื่อฝังแบบอักษร true type สำหรับอักขระ ASCII 32-127. แบบอักษรสำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**.

**คืนค่า:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True เพื่อฝังแบบอักษร true type สำหรับอักขระ ASCII 32-127. แบบอักษรสำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

คืนค่า หรือกำหนดอาร์เรย์ของชื่อฟอนท์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรพิจารณาว่าเป็นทั่วไป. อ่าน/เขียน String[].

**คืนค่า:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

คืนค่า หรือกำหนดอาร์เรย์ของชื่อฟอนท์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรพิจารณาว่าเป็นทั่วไป. อ่าน/เขียน String[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

กำหนดว่าต้องฝังอักขระทั้งหมดของแบบอักษรหรือเพียงส่วนที่ใช้. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

กำหนดว่าต้องฝังอักขระทั้งหมดของแบบอักษรหรือเพียงส่วนที่ใช้. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

ระบุว่าข้อความควรถูกแปลงเป็นบิตแมพและบันทึกเป็น PDF เมื่อแบบอักษรไม่รองรับการทำตัวหนา. วิธีนี้อาจเพิ่มคุณภาพของข้อความใน PDF ที่ได้สำหรับแบบอักษรบางชนิด. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

ระบุว่าข้อความควรถูกแปลงเป็นบิตแมพและบันทึกเป็น PDF เมื่อแบบอักษรไม่รองรับการทำตัวหนา. วิธีนี้อาจเพิ่มคุณภาพของข้อความใน PDF ที่ได้สำหรับแบบอักษรบางชนิด. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของรูป JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีรูป JPEG.

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของรูปภายในเอกสารเมื่อบันทึกเป็นรูปแบบ PDF. ค่าจะอยู่ระหว่าง 0 ถึง 100 โดย 0 หมายถึงคุณภาพแย่สุดแต่บีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่บีบอัดต่ำสุด.

ค่าตั้งต้นคือ **100**.

**คืนค่า:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของรูป JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีรูป JPEG.

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของรูปภายในเอกสารเมื่อบันทึกเป็นรูปแบบ PDF. ค่าจะอยู่ระหว่าง 0 ถึง 100 โดย 0 หมายถึงคุณภาพแย่สุดแต่บีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่บีบอัดต่ำสุด.

ค่าตั้งต้นคือ **100**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

ระดับการสอดคล้องที่ต้องการสำหรับเอกสาร PDF ที่สร้าง. อ่าน/เขียน [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

ค่าเริ่มต้นคือ [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**คืนค่า:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

ระดับการสอดคล้องที่ต้องการสำหรับเอกสาร PDF ที่สร้าง. อ่าน/เขียน [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

ค่าเริ่มต้นคือ [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

การตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

การตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

ประกอบด้วยชุดของแฟล็กที่ระบุสิทธิ์การเข้าถึงที่จะให้เมื่อเปิดเอกสารด้วยการเข้าถึงของผู้ใช้. ดู [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

ประกอบด้วยชุดของแฟล็กที่ระบุสิทธิ์การเข้าถึงที่จะให้เมื่อเปิดเอกสารด้วยการเข้าถึงของผู้ใช้. ดู [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract boolean getSaveMetafilesAsPng()
```

True เพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

**คืนค่า:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True เพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

คืนค่า หรือกำหนดค่าที่กำหนดความละเอียดของรูปภาพภายในเอกสาร PDF. อ่าน/เขียน float.

ค่า: ผลของพารามิเตอร์นี้ขึ้นอยู่กับหลายปัจจัย. อัลกอริทึมพยายามหาขนาดภาพเอาต์พุตที่ดีที่สุดตามค่าคุณสมบัติ, ขนาดรูปภาพต้นฉบับและขนาดเฟรมรูปภาพ. การใช้ค่าคุณสมบัติที่คล้ายกันอาจให้ผลลัพธ์เดียวกัน. แนะนำให้ใช้ขั้น 16 หรือ 32 เพื่อให้เห็นผล.

คุณสมบัตินี้มีผลต่อขนาดไฟล์, เวลาในการส่งออกและคุณภาพของรูปภาพ.

ค่าตั้งต้นคือ **96**.

**คืนค่า:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

คืนค่า หรือกำหนดค่าที่กำหนดความละเอียดของรูปภาพภายในเอกสาร PDF. อ่าน/เขียน float.

ค่า: ผลของพารามิเตอร์นี้ขึ้นอยู่กับหลายปัจจัย. อัลกอริทึมพยายามหาขนาดภาพเอาต์พุตที่ดีที่สุดตามค่าคุณสมบัติ, ขนาดรูปภาพต้นฉบับและขนาดเฟรมรูปภาพ. การใช้ค่าคุณสมบัติที่คล้ายกันอาจให้ผลลัพธ์เดียวกัน. แนะนำให้ใช้ขั้น 16 หรือ 32 เพื่อให้เห็นผล.

คุณสมบัตินี้มีผลต่อขนาดไฟล์, เวลาในการส่งออกและคุณภาพของรูปภาพ.

ค่าตั้งต้นคือ **96**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True เพื่อวาดกรอบสีดำรอบสไลด์แต่ละสไลด์. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True เพื่อวาดกรอบสีดำรอบสไลด์แต่ละสไลด์. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

รับหรือกำหนดสีโปร่งใสของภาพ.

ค่า: สีโปร่งใสของภาพ.

**คืนค่า:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

รับหรือกำหนดสีโปร่งใสของภาพ.

ค่า: สีโปร่งใสของภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

นำสีโปร่งใสที่ระบุไปใช้กับภาพหากเป็น true.

**คืนค่า:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

นำสีโปร่งใสที่ระบุไปใช้กับภาพหากเป็น true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
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
public abstract void setIncludeOleData(boolean value)
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