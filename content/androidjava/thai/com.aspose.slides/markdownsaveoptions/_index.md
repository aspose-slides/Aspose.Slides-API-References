---
title: MarkdownSaveOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอเป็น markdown.
type: docs
url: /th/com.aspose.slides/markdownsaveoptions/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

แสดงตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอเป็น markdown.

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
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Ctor. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getExportType()](#getExportType--) | ระบุสเปคลิกรหัส markdown ที่ใช้แปลงการนำเสนอ. |
| [setExportType(int value)](#setExportType-int-) | ระบุสเปคลิกรหัส markdown ที่ใช้แปลงการนำเสนอ. |
| [getBasePath()](#getBasePath--) | ระบุเส้นทางฐานที่เอกสารพร้อมทรัพยากรจะถูกบันทึก. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | ระบุเส้นทางฐานที่เอกสารพร้อมทรัพยากรจะถูกบันทึก. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | ระบุชื่อโฟลเดอร์เพื่อบันทึกรูปภาพ. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | ระบุชื่อโฟลเดอร์เพื่อบันทึกรูปภาพ. |
| [getNewLineType()](#getNewLineType--) | ระบุว่ากระบวนการสร้างเอกสารควรใช้บรรทัดใหม่ \\r(Macintosh) หรือ \\n(Unix) หรือ \\r\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | ระบุว่ากระบวนการสร้างเอกสารควรใช้บรรทัดใหม่ \\r(Macintosh) หรือ \\n(Unix) หรือ \\r\\n(Windows). |
| [getShowComments()](#getShowComments--) | ระบุว่ากระบวนการสร้างเอกสารควรแสดงความคิดเห็นหรือไม่. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | ระบุว่ากระบวนการสร้างเอกสารควรแสดงความคิดเห็นหรือไม่. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่ากระบวนการสร้างเอกสารควรรวมสไลด์ที่ซ่อนไว้หรือไม่. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่ากระบวนการสร้างเอกสารควรรวมสไลด์ที่ซ่อนไว้หรือไม่. |
| [getShowSlideNumber()](#getShowSlideNumber--) | ระบุว่ากระบวนการสร้างเอกสารควรแสดงหมายเลขของแต่ละสไลด์หรือไม่. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | ระบุว่ากระบวนการสร้างเอกสารควรแสดงหมายเลขของแต่ละสไลด์หรือไม่. |
| [getFlavor()](#getFlavor--) | ระบุสเปคลิกรหัส markdown ที่ใช้แปลงการนำเสนอ. |
| [setFlavor(int value)](#setFlavor-int-) | ระบุสเปคลิกรหัส markdown ที่ใช้แปลงการนำเสนอ. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | รับหรือกำหนดสตริงรูปแบบที่ใช้สำหรับหัวข้อหมายเลขสไลด์ในผลลัพธ์ Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | รับหรือกำหนดสตริงรูปแบบที่ใช้สำหรับหัวข้อหมายเลขสไลด์ในผลลัพธ์ Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | ระบุวิธีการจัดการกับอักขระช่องว่างปกติที่ซ้ำกันระหว่างการส่งออกเป็น Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | ระบุวิธีการจัดการกับอักขระช่องว่างปกติที่ซ้ำกันระหว่างการส่งออกเป็น Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | หากตั้งค่าเป็น true จะลบบรรทัดที่ว่างหรือมีเพียงช่องว่างออกจากผลลัพธ์ Markdown ขั้นสุดท้าย. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | หากตั้งค่าเป็น true จะลบบรรทัดที่ว่างหรือมีเพียงช่องว่างออกจากผลลัพธ์ Markdown ขั้นสุดท้าย. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | เกิดขึ้นสำหรับแต่ละภาพที่ไม่ใช่ SVG (bitmap หรือ metafile) ระหว่างการส่งออกเป็น Markdown. อนุญาตให้กำหนดวิธีการบันทึกและอ้างอิงภาพได้. หากไม่จัดการ ภาพจะถูกบันทึกในเครื่องโดยใช้ลิงก์แบบสัมพันธ์. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | เกิดขึ้นสำหรับแต่ละภาพ SVG ระหว่างการส่งออกเป็น Markdown. อนุญาตให้แทนที่การบันทึกและการสร้างลิงก์เริ่มต้นได้. หากไม่จัดการ SVG จะถูกบันทึกในเครื่องโดยใช้ลิงก์แบบสัมพันธ์. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


Ctor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```


ระบุสเปคลิกรหัส markdown ที่ใช้แปลงการนำเสนอ. ค่าเริ่มต้นคือ  TextOnly .

**ผลลัพธ์:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


ระบุสเปคลิกรหัส markdown ที่ใช้แปลงการนำเสนอ. ค่าเริ่มต้นคือ  TextOnly .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


ระบุเส้นทางฐานที่เอกสารพร้อมทรัพยากรจะถูกบันทึก. ค่าเริ่มต้นคือไดเรกทอรีปัจจุบันของแอปพลิเคชัน.

**ผลลัพธ์:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


ระบุเส้นทางฐานที่เอกสารพร้อมทรัพยากรจะถูกบันทึก. ค่าเริ่มต้นคือไดเรกทอรีปัจจุบันของแอปพลิเคชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


ระบุชื่อโฟลเดอร์เพื่อบันทึกรูปภาพ. ค่าเริ่มต้นคือ  Images .

**ผลลัพธ์:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


ระบุชื่อโฟลเดอร์เพื่อบันทึกรูปภาพ. ค่าเริ่มต้นคือ  Images .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


ระบุว่ากระบวนการสร้างเอกสารควรใช้บรรทัดใหม่ \\r(Macintosh) หรือ \\n(Unix) หรือ \\r\\n(Windows). ค่าเริ่มต้นคือ  Unix .

**ผลลัพธ์:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


ระบุว่ากระบวนการสร้างเอกสารควรใช้บรรทัดใหม่ \\r(Macintosh) หรือ \\n(Unix) หรือ \\r\\n(Windows). ค่าเริ่มต้นคือ  Unix .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


ระบุว่ากระบวนการสร้างเอกสารควรแสดงความคิดเห็นหรือไม่. ค่าเริ่มต้นคือ false.

**ผลลัพธ์:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


ระบุว่ากระบวนการสร้างเอกสารควรแสดงความคิดเห็นหรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


ระบุว่ากระบวนการสร้างเอกสารควรรวมสไลด์ที่ซ่อนไว้หรือไม่. ค่าเริ่มต้นคือ false.

**ผลลัพธ์:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


ระบุว่ากระบวนการสร้างเอกสารควรรวมสไลด์ที่ซ่อนไว้หรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


ระบุว่ากระบวนการสร้างเอกสารควรแสดงหมายเลขของแต่ละสไลด์หรือไม่. ค่าเริ่มต้นคือ false.

**ผลลัพธ์:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


ระบุว่ากระบวนการสร้างเอกสารควรแสดงหมายเลขของแต่ละสไลด์หรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


ระบุสเปคลิกรหัส markdown ที่ใช้แปลงการนำเสนอ. ค่าเริ่มต้นคือ  Multi-markdown .

**ผลลัพธ์:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


ระบุสเปคลิกรหัส markdown ที่ใช้แปลงการนำเสนอ. ค่าเริ่มต้นคือ  Multi-markdown .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```


รับหรือกำหนดสตริงรูปแบบที่ใช้สำหรับหัวข้อหมายเลขสไลด์ในผลลัพธ์ Markdown. รูปแบบต้องมีตัวแทน "\{0\}" ซึ่งจะถูกแทนที่ด้วยหมายเลขสไลด์ระหว่างการส่งออก. ตัวอย่าง: "\# Slide \{0\}" จะสร้าง "\# Slide 1", "\# Slide 2", เป็นต้น.

**ผลลัพธ์:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```


รับหรือกำหนดสตริงรูปแบบที่ใช้สำหรับหัวข้อหมายเลขสไลด์ในผลลัพธ์ Markdown. รูปแบบต้องมีตัวแทน "\{0\}" ซึ่งจะถูกแทนที่ด้วยหมายเลขสไลด์ระหว่างการส่งออก. ตัวอย่าง: "\# Slide \{0\}" จะสร้าง "\# Slide 1", "\# Slide 2", เป็นต้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```


ระบุวิธีการจัดการกับอักขระช่องว่างปกติที่ซ้ำกันระหว่างการส่งออกเป็น Markdown. คุณสมบัตินี้กำหนดว่าช่องว่างต่อเนื่องจะ: - คงไว้เป็นอักขระช่องว่างปกติ, - สลับระหว่างช่องว่างปกติและหน่วยความหมาย non-breaking space (�), - หรือแทนที่ทั้งหมด (หลังจากอันแรก) ด้วย non-breaking space เพื่อรักษาการจัดแนวในผลลัพธ์ Markdown. ค่าเริ่มต้นคือ [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**ผลลัพธ์:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```


ระบุวิธีการจัดการกับอักขระช่องว่างปกติที่ซ้ำกันระหว่างการส่งออกเป็น Markdown. คุณสมบัตินี้กำหนดว่าช่องว่างต่อเนื่องจะ: - คงไว้เป็นอักขระช่องว่างปกติ, - สลับระหว่างช่องว่างปกติและหน่วยความหมาย non-breaking space (�), - หรือแทนที่ทั้งหมด (หลังจากอันแรก) ด้วย non-breaking space เพื่อรักษาการจัดแนวในผลลัพธ์ Markdown. ค่าเริ่มต้นคือ [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```


หากตั้งค่าเป็น true จะลบบรรทัดที่ว่างหรือมีเพียงช่องว่างออกจากผลลัพธ์ Markdown ขั้นสุดท้าย. ค่าเริ่มต้นคือ false.

**ผลลัพธ์:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```


หากตั้งค่าเป็น true จะลบบรรทัดที่ว่างหรือมีเพียงช่องว่างออกจากผลลัพธ์ Markdown ขั้นสุดท้าย. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```


เกิดขึ้นสำหรับแต่ละภาพที่ไม่ใช่ SVG (bitmap หรือ metafile) ระหว่างการส่งออกเป็น Markdown. อนุญาตให้กำหนดวิธีการบันทึกและอ้างอิงภาพได้. หากไม่จัดการ ภาพจะถูกบันทึกในเครื่องโดยใช้ลิงก์แบบสัมพันธ์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | เหตุการณ์การบันทึกภาพ Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```


เกิดขึ้นสำหรับแต่ละภาพ SVG ระหว่างการส่งออกเป็น Markdown. อนุญาตให้แทนที่การบันทึกและการสร้างลิงก์เริ่มต้นได้. หากไม่จัดการ SVG จะถูกบันทึกในเครื่องโดยใช้ลิงก์แบบสัมพันธ์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | เหตุการณ์การบันทึกภาพ SVG Markdown. |