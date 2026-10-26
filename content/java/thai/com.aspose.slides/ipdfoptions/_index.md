---
title: IPdfOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ Pdf.
type: docs
url: /th/com.aspose.slides/ipdfoptions/
---
**ส่วนต่อประสานที่นำไปใช้งานทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกไฟล์งานนำเสนอในรูปแบบ Pdf.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | ระบุประเภทการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร |
| [setTextCompression(int value)](#setTextCompression-int-) | ระบุประเภทการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | ระบุว่าควรเลือกการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนค่าปริยาย) สำหรับแต่ละภาพโดยอัตโนมัติหรือไม่ |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | ระบุว่าควรเลือกการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนค่าปริยาย) สำหรับแต่ละภาพโดยอัตโนมัติหรือไม่ |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | จริงเพื่อฝังฟอนต์ True Type สำหรับอักขระ ASCII 32-127 |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | จริงเพื่อฝังฟอนต์ True Type สำหรับอักขระ ASCII 32-127 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | คืนค่า หรือกำหนดอาร์เรย์ของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรพิจารณาว่าเป็นฟอนต์ทั่วไป |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | คืนค่า หรือกำหนดอาร์เรย์ของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรพิจารณาว่าเป็นฟอนต์ทั่วไป |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | กำหนดว่าควรฝังอักขระทั้งหมดของฟอนต์หรือเพียงส่วนย่อยที่ใช้ |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | กำหนดว่าควรฝังอักขระทั้งหมดของฟอนต์หรือเพียงส่วนย่อยที่ใช้ |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | ระบุว่าข้อความควรถูกเรสเตอร์ไทซ์เป็นบิตแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับสไตล์หนา |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | ระบุว่าข้อความควรถูกเรสเตอร์ไทซ์เป็นบิตแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับสไตล์หนา |
| [getJpegQuality()](#getJpegQuality--) | คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF |
| [getCompliance()](#getCompliance--) | ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้าง |
| [setCompliance(int value)](#setCompliance-int-) | ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้าง |
| [getPassword()](#getPassword--) | ตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF |
| [setPassword(String value)](#setPassword-java.lang.String-) | ตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF |
| [getAccessPermissions()](#getAccessPermissions--) | มีชุดของแฟล็กที่ระบุว่าควรให้สิทธิ์การเข้าถึงใดเมื่อเปิดเอกสารด้วยสิทธิ์ผู้ใช้ |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | มีชุดของแฟล็กที่ระบุว่าควรให้สิทธิ์การเข้าถึงใดเมื่อเปิดเอกสารด้วยสิทธิ์ผู้ใช้ |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | จริงเพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | จริงเพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG |
| [getSufficientResolution()](#getSufficientResolution--) | คืนค่า หรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | คืนค่า หรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | จริงเพื่อวาดกรอบสีดำรอบแต่ละสไลด์ |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | จริงเพื่อวาดกรอบสีดำรอบแต่ละสไลด์ |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้ากระดาษเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้ากระดาษเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [getImageTransparentColor()](#getImageTransparentColor--) | รับหรือกำหนดสีโปร่งแสงของภาพ |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | รับหรือกำหนดสีโปร่งแสงของภาพ |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | ใช้สีโปร่งแสงที่กำหนดกับภาพหากเป็นจริง |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | ใช้สีโปร่งแสงที่กำหนดกับภาพหากเป็นจริง |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก |
| [getIncludeOleData()](#getIncludeOleData--) | จริงเพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้ |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | จริงเพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้ |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

ระบุประเภทการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร. อ่าน/เขียน [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

ค่าเริ่มต้นคือ [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**คืนค่า:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
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
public abstract boolean getBestImagesCompressionRatio()
```

ระบุว่าควรเลือกการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนค่าปริยาย) สำหรับแต่ละภาพโดยอัตโนมัติหรือไม่. หากตั้งเป็นจริง ระบบจะเลือกอัลกอริทึมการบีบอัดที่เหมาะสมที่สุดสำหรับแต่ละภาพ ทำให้ขนาด PDF ที่ได้เล็กลง.

--------------------

การเลือกอัตราการบีบอัดภาพที่ดีที่สุดใช้ทรัพยากรคอมพิวเตอร์มากและต้องใช้ RAM เพิ่มเติม; ตัวเลือกนี้มีค่าเริ่มต้นเป็น false.

--------------------

ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

ระบุว่าควรเลือกการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนค่าปริยาย) สำหรับแต่ละภาพโดยอัตโนมัติหรือไม่. หากตั้งเป็นจริง ระบบจะเลือกอัลกอริทึมการบีบอัดที่เหมาะสมที่สุดสำหรับแต่ละภาพ ทำให้ขนาด PDF ที่ได้เล็กลง.

--------------------

การเลือกอัตราการบีบอัดภาพที่ดีที่สุดใช้ทรัพยากรคอมพิวเตอร์มากและต้องใช้ RAM เพิ่มเติม; ตัวเลือกนี้มีค่าเริ่มต้นเป็น false.

--------------------

ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

จริงเพื่อฝังฟอนต์ True Type สำหรับอักขระ ASCII 32-127. ฟอนต์สำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**.

**คืนค่า:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

จริงเพื่อฝังฟอนต์ True Type สำหรับอักขระ ASCII 32-127. ฟอนต์สำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

คืนค่า หรือกำหนดอาร์เรย์ของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรพิจารณาว่าเป็นฟอนต์ทั่วไป. อ่าน/เขียน String[].

**คืนค่า:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

คืนค่า หรือกำหนดอาร์เรย์ของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรพิจารณาว่าเป็นฟอนต์ทั่วไป. อ่าน/เขียน String[].

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

กำหนดว่าควรฝังอักขระทั้งหมดของฟอนต์หรือเพียงส่วนย่อยที่ใช้. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

กำหนดว่าควรฝังอักขระทั้งหมดของฟอนต์หรือเพียงส่วนย่อยที่ใช้. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

ระบุว่าข้อความควรถูกเรสเตอร์ไทซ์เป็นบิตแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับสไตล์หนา. วิธีนี้อาจเพิ่มคุณภาพของข้อความใน PDF สำหรับฟอนต์บางตัว. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

ระบุว่าข้อความควรถูกเรสเตอร์ไทซ์เป็นบิตแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่รองรับสไตล์หนา. วิธีนี้อาจเพิ่มคุณภาพของข้อความใน PDF สำหรับฟอนต์บางตัว. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG.

ใช้คุณสมบัตินี้เพื่อกำหนดหรือรับคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็น PDF. ค่าจะอยู่ระหว่าง 0 ถึง 100, โดย 0 หมายถึงคุณภาพต่ำที่สุดแต่บีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่บีบอัดต่ำสุด.

ค่าเริ่มต้นคือ **100**.

**คืนค่า:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG.

ใช้คุณสมบัตินี้เพื่อกำหนดหรือรับคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็น PDF. ค่าจะอยู่ระหว่าง 0 ถึง 100, โดย 0 หมายถึงคุณภาพต่ำที่สุดแต่บีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่บีบอัดต่ำสุด.

ค่าเริ่มต้นคือ **100**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้าง. อ่าน/เขียน [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

ค่าเริ่มต้นคือ [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**คืนค่า:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้าง. อ่าน/เขียน [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

ค่าเริ่มต้นคือ [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

ตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

ตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

มีชุดของแฟล็กที่ระบุว่าควรให้สิทธิ์การเข้าถึงใดเมื่อเปิดเอกสารด้วยสิทธิ์ผู้ใช้. ดู [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

มีชุดของแฟล็กที่ระบุว่าควรให้สิทธิ์การเข้าถึงใดเมื่อเปิดเอกสารด้วยสิทธิ์ผู้ใช้. ดู [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract boolean getSaveMetafilesAsPng()
```

จริงเพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**. เอกสาร PDF สามารถมีกราฟิกเวกเตอร์และภาพราสเตอร์ได้. หากตั้งเป็น true เมต้าไฟล์จะถูกแปลงเป็น PNG แล้วบันทึกเป็นภาพราสเตอร์. หากตั้งเป็น false เมต้าไฟล์จะถูกแปลงเป็นกราฟิกเวกเตอร์ของ PDF. วิธีแต่ละแบบมีข้อดีและข้อเสีย. ตัวอย่างเช่น หากแปลงเป็น PNG อาจสูญเสียคุณภาพเมื่อสเกลเอกสาร. หากแปลงเป็นกราฟิกเวกเตอร์อาจทำให้เครื่องมือดู PDF ทำงานช้าลง.

**คืนค่า:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

จริงเพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**. เอกสาร PDF สามารถมีกราฟิกเวกเตอร์และภาพราสเตอร์ได้. หากตั้งเป็น true เมต้าไฟล์จะถูกแปลงเป็น PNG แล้วบันทึกเป็นภาพราสเตอร์. หากตั้งเป็น false เมต้าไฟล์จะถูกแปลงเป็นกราฟิกเวกเตอร์ของ PDF. วิธีแต่ละแบบมีข้อดีและข้อเสีย. ตัวอย่างเช่น หากแปลงเป็น PNG อาจสูญเสียคุณภาพเมื่อสเกลเอกสาร. หากแปลงเป็นกราฟิกเวกเตอร์อาจทำให้เครื่องมือดู PDF ทำงานช้าลง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

คืนค่า หรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. อ่าน/เขียน float.

ค่า: ผลของพารามิเตอร์นี้ขึ้นอยู่กับหลายปัจจัย. อัลกอริทึมพยายามให้ขนาดภาพเอาต์พุตที่ดีที่สุดตามค่าคุณสมบัติ, ขนาดภาพต้นแบบและขนาดกรอบภาพ. การใช้ค่าที่คล้ายกันอาจให้ผลลัพธ์เหมือนกัน. แนะนำให้ใช้ขั้น 16 หรือ 32 เพื่อให้เห็นผล.

--------------------

คุณสมบัตินี้ส่งผลต่อขนาดไฟล์, เวลาแปลงและคุณภาพภาพ.

ค่าเริ่มต้นคือ **96**.

**คืนค่า:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

คืนค่า หรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. อ่าน/เขียน float.

ค่า: ผลของพารามิเตอร์นี้ขึ้นอยู่กับหลายปัจจัย. อัลกอริทึมพยายามให้ขนาดภาพเอาต์พุตที่ดีที่สุดตามค่าคุณสมบัติ, ขนาดภาพต้นแบบและขนาดกรอบภาพ. การใช้ค่าที่คล้ายกันอาจให้ผลลัพธ์เหมือนกัน. แนะนำให้ใช้ขั้น 16 หรือ 32 เพื่อให้เห็นผล.

--------------------

คุณสมบัตินี้ส่งผลต่อขนาดไฟล์, เวลาแปลงและคุณภาพภาพ.

ค่าเริ่มต้นคือ **96**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

จริงเพื่อวาดกรอบสีดำรอบแต่ละสไลด์. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

จริงเพื่อวาดกรอบสีดำรอบแต่ละสไลด์. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้ากระดาษเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้ากระดาษเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

รับหรือกำหนดสีโปร่งแสงของภาพ.

ค่า: สีโปร่งแสงของภาพ.

**คืนค่า:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract Color getImageTransparentColor()
```

รับหรือกำหนดสีโปร่งแสงของภาพ.

ค่า: สีโปร่งแสงของภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

ใช้สีโปร่งแสงที่กำหนดกับภาพหากเป็นจริง.

**คืนค่า:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

ใช้สีโปร่งแสงที่กำหนดกับภาพหากเป็นจริง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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

จริงเพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. อ่าน/เขียน boolean.

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

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

จริงเพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. อ่าน/เขียน boolean.

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

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |