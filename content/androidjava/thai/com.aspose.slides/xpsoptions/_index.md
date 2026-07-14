---
title: XpsOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ XPS.
type: docs
url: /th/com.aspose.slides/xpsoptions/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)  
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ XPS

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // บันทึกงานนำเสนอเป็นเอกสาร XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // สร้างอ็อบเจ็กต์ของคลาส TiffOptions
>      XpsOptions options = new XpsOptions();
>      // บันทึก MetaFiles เป็น PNG
>      options.setSaveMetafilesAsPng(true);
>      // บันทึกงานนำเสนอเป็นเอกสาร XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | คอนสตรัคเตอร์เริ่มต้น |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าเอกสารที่สร้างขึ้นควรรวมสไลด์ที่ซ่อนไว้หรือไม่ |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าเอกสารที่สร้างขึ้นควรรวมสไลด์ที่ซ่อนไว้หรือไม่ |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | กำหนดเป็น true เพื่อแปลงไฟล์เมตาทั้งหมดที่ใช้ในงานนำเสนอเป็นรูปภาพ PNG |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | กำหนดเป็น true เพื่อแปลงไฟล์เมตาทั้งหมดที่ใช้ในงานนำเสนอเป็นรูปภาพ PNG |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | กำหนดเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์ |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | กำหนดเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์ |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

คอนสตรัคเตอร์เริ่มต้น

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

ระบุว่าเอกสารที่สร้างขึ้นควรรวมสไลด์ที่ซ่อนไว้หรือไม่ ค่าเริ่มต้นคือ false

**คืนค่า:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

ระบุว่าเอกสารที่สร้างขึ้นควรรวมสไลด์ที่ซ่อนไว้หรือไม่ ค่าเริ่มต้นคือ false

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

กำหนดเป็น true เพื่อแปลงไฟล์เมตาทั้งหมดที่ใช้ในงานนำเสนอเป็นรูปภาพ PNG  boolean อ่าน/เขียน

--------------------

ค่าเริ่มต้นคือ **true**.

**คืนค่า:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

กำหนดเป็น true เพื่อแปลงไฟล์เมตาทั้งหมดที่ใช้ในงานนำเสนอเป็นรูปภาพ PNG  boolean อ่าน/เขียน

--------------------

ค่าเริ่มต้นคือ **true**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

กำหนดเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์  boolean อ่าน/เขียน

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

กำหนดเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์  boolean อ่าน/เขียน

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |