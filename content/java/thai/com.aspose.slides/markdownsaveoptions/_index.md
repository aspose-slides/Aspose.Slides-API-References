---
title: MarkdownSaveOptions
second_title: อ้างอิง API Aspose.Slides สำหรับ Java
description: แสดงตัวเลือกที่ใช้ควบคุมวิธีการบันทึกงานนำเสนอเป็น markdown.
type: docs
url: /th/com.aspose.slides/markdownsaveoptions/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

อธิบายตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็น markdown

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | ตัวสร้าง |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getExportType()](#getExportType--) | ระบุสเปค markdown สำหรับแปลงงานนำเสนอ |
| [setExportType(int value)](#setExportType-int-) | ระบุสเปค markdown สำหรับแปลงงานนำเสนอ |
| [getBasePath()](#getBasePath--) | ระบุเส้นทางฐานที่เอกสารพร้อมทรัพยากรจะถูกบันทึก |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | ระบุเส้นทางฐานที่เอกสารพร้อมทรัพยากรจะถูกบันทึก |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | ระบุชื่อโฟลเดอร์สำหรับบันทึกรูปภาพ |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | ระบุชื่อโฟลเดอร์สำหรับบันทึกรูปภาพ |
| [getNewLineType()](#getNewLineType--) | ระบุว่าตัวเอกสารที่สร้างควรใช้บรรทัดใหม่ \\\\r (Macintosh) หรือ \\\\n (Unix) หรือ \\\\r\\\\n (Windows) |
| [setNewLineType(int value)](#setNewLineType-int-) | ระบุว่าตัวเอกสารที่สร้างควรใช้บรรทัดใหม่ \\\\r (Macintosh) หรือ \\\\n (Unix) หรือ \\\\r\\\\n (Windows) |
| [getShowComments()](#getShowComments--) | ระบุว่าตัวเอกสารที่สร้างจะแสดงความคิดเห็นหรือไม่ |
| [setShowComments(boolean value)](#setShowComments-boolean-) | ระบุว่าตัวเอกสารที่สร้างจะแสดงความคิดเห็นหรือไม่ |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าตัวเอกสารที่สร้างจะรวมสไลด์ที่ซ่อนอยู่หรือไม่ |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าตัวเอกสารที่สร้างจะรวมสไลด์ที่ซ่อนอยู่หรือไม่ |
| [getShowSlideNumber()](#getShowSlideNumber--) | ระบุว่าตัวเอกสารที่สร้างจะแสดงหมายเลขของแต่ละสไลด์หรือไม่ |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | ระบุว่าตัวเอกสารที่สร้างจะแสดงหมายเลขของแต่ละสไลด์หรือไม่ |
| [getFlavor()](#getFlavor--) | ระบุสเปค markdown สำหรับแปลงงานนำเสนอ |
| [setFlavor(int value)](#setFlavor-int-) | ระบุสเปค markdown สำหรับแปลงงานนำเสนอ |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | รับหรือกำหนดสตริงรูปแบบที่ใช้สำหรับหัวข้อหมายเลขสไลด์ในผลลัพธ์ Markdown |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | รับหรือกำหนดสตริงรูปแบบที่ใช้สำหรับหัวข้อหมายเลขสไลด์ในผลลัพธ์ Markdown |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | ระบุวิธีจัดการกับอักขระช่องว่างที่ซ้ำกันในการส่งออก Markdown |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | ระบุวิธีจัดการกับอักขระช่องว่างที่ซ้ำกันในการส่งออก Markdown |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | หากตั้งเป็น true จะลบบรรทัดว่างหรือบรรทัดที่มีเฉพาะช่องว่างออกจากผลลัพธ์ Markdown |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | หากตั้งเป็น true จะลบบรรทัดว่างหรือบรรทัดที่มีเฉพาะช่องว่างออกจากผลลัพธ์ Markdown |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | เกิดขึ้นสำหรับแต่ละรูปภาพที่ไม่ใช่ SVG (bitmap หรือ metafile) ระหว่างการส่งออก Markdown |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | เกิดขึ้นสำหรับแต่ละรูปภาพ SVG ระหว่างการส่งออก Markdown |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


ตัวสร้าง

### getExportType() {#getExportType--}
```
public final int getExportType()
```


ระบุสเปค markdown สำหรับแปลงงานนำเสนอ ค่าเริ่มต้นคือ TextOnly

**คืนค่า:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


ระบุสเปค markdown สำหรับแปลงงานนำเสนอ ค่าเริ่มต้นคือ TextOnly

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


ระบุเส้นทางฐานที่เอกสารพร้อมทรัพยากรจะถูกบันทึก ค่าเริ่มต้นคือไดเรกทอรีปัจจุบันของแอปพลิเคชัน

**คืนค่า:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


ระบุเส้นทางฐานที่เอกสารพร้อมทรัพยากรจะถูกบันทึก ค่าเริ่มต้นคือไดเรกทอรีปัจจุบันของแอปพลิเคชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


ระบุชื่อโฟลเดอร์สำหรับบันทึกรูปภาพ ค่าเริ่มต้นคือ Images

**คืนค่า:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


ระบุชื่อโฟลเดอร์สำหรับบันทึกรูปภาพ ค่าเริ่มต้นคือ Images

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


ระบุว่าตัวเอกสารที่สร้างควรใช้บรรทัดใหม่ \\\\r (Macintosh) หรือ \\\\n (Unix) หรือ \\\\r\\\\n (Windows) ค่าเริ่มต้นคือ Unix

**คืนค่า:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


ระบุว่าตัวเอกสารที่สร้างควรใช้บรรทัดใหม่ \\\\r (Macintosh) หรือ \\\\n (Unix) หรือ \\\\r\\\\n (Windows) ค่าเริ่มต้นคือ Unix

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


ระบุว่าตัวเอกสารที่สร้างจะแสดงความคิดเห็นหรือไม่ ค่าเริ่มต้นคือ false

**คืนค่า:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


ระบุว่าตัวเอกสารที่สร้างจะแสดงความคิดเห็นหรือไม่ ค่าเริ่มต้นคือ false

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


ระบุว่าตัวเอกสารที่สร้างจะรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false

**คืนค่า:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


ระบุว่าตัวเอกสารที่สร้างจะรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


ระบุว่าตัวเอกสารที่สร้างจะแสดงหมายเลขของแต่ละสไลด์หรือไม่ ค่าเริ่มต้นคือ false

**คืนค่า:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


ระบุว่าตัวเอกสารที่สร้างจะแสดงหมายเลขของแต่ละสไลด์หรือไม่ ค่าเริ่มต้นคือ false

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


ระบุสเปค markdown สำหรับแปลงงานนำเสนอ ค่าเริ่มต้นคือ Multi-markdown

**คืนค่า:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


ระบุสเปค markdown สำหรับแปลงงานนำเสนอ ค่าเริ่มต้นคือ Multi-markdown

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```


รับหรือกำหนดสตริงรูปแบบที่ใช้สำหรับหัวข้อหมายเลขสไลด์ในผลลัพธ์ Markdown รูปแบบต้องมีตัวแทน "\{0\}" ซึ่งจะถูกแทนที่ด้วยหมายเลขสไลด์ในระหว่างการส่งออก ตัวอย่าง: "\# Slide \{0\}" จะให้ผลลัพธ์ "\# Slide 1", "\# Slide 2" ฯลฯ

**คืนค่า:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```


รับหรือกำหนดสติงรูปแบบที่ใช้สำหรับหัวข้อหมายเลขสไลด์ในผลลัพธ์ Markdown รูปแบบต้องมีตัวแทน "\{0\}" ซึ่งจะถูกแทนที่ด้วยหมายเลขสไลด์ในระหว่างการส่งออก ตัวอย่าง: "\# Slide \{0\}" จะให้ผลลัพธ์ "\# Slide 1", "\# Slide 2" ฯลฯ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```


ระบุวิธีจัดการกับอักขระช่องว่างปกติที่ซ้ำกันในการส่งออก Markdown คุณสมบัตินี้กำหนดว่าช่องว่างต่อเนื่องจะ: - คงไว้เป็นอักขระช่องว่างปกติ - สลับระหว่างช่องว่างปกติและเอนทิตี non-breaking space (�) - หรือแทนที่ทั้งหมด (หลังจากอักขระแรก) ด้วย non-breaking space เพื่อรักษาการจัดแนวในผลลัพธ์ Markdown ค่าเริ่มต้นคือ [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp)

**คืนค่า:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```


ระบุวิธีจัดการกับอักขระช่องว่างปกติที่ซ้ำกันในการส่งออก Markdown คุณสมบัตินี้กำหนดว่าช่องว่างต่อเนื่องจะ: - คงไว้เป็นอักขระช่องว่างปกติ - สลับระหว่างช่องว่างปกติและเอนทิตี non-breaking space (�) - หรือแทนที่ทั้งหมด (หลังจากอักขระแรก) ด้วย non-breaking space เพื่อรักษาการจัดแนวในผลลัพธ์ Markdown ค่าเริ่มต้นคือ [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```


หากตั้งค่าเป็น true จะลบบรรทัดที่ว่างหรือมีแต่ช่องว่างออกจากผลลัพธ์ Markdown ค่าเริ่มต้นคือ false

**คืนค่า:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```


หากตั้งค่าเป็น true จะลบบรรทัดที่ว่างหรือมีแต่ช่องว่างออกจากผลลัพธ์ Markdown ค่าเริ่มต้นคือ false

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```


เกิดขึ้นสำหรับแต่ละรูปภาพที่ไม่ใช่ SVG (bitmap หรือ metafile) ระหว่างการส่งออก Markdown ให้คุณกำหนดวิธีการบันทึกและอ้างอิงรูปภาพ หากไม่ได้จัดการรูปภาพจะถูกบันทึกในเครื่องพร้อมลิงก์สัมพันธ์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | เหตุการณ์บันทึกรูปภาพ Markdown |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```


เกิดขึ้นสำหรับแต่ละรูปภาพ SVG ระหว่างการส่งออก Markdown ให้คุณกำหนดวิธีการบันทึกและสร้างลิงก์ หากไม่ได้จัดการ SVG จะถูกบันทึกในเครื่องพร้อมลิงก์สัมพันธ์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | เหตุการณ์บันทึก SVG Markdown |