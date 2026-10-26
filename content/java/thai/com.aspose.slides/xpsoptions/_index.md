---
title: XpsOptions
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: จัดหาตัวเลือกที่ควบคุมการบันทึกการนำเสนอในรูปแบบ XPS
type: docs
url: /th/com.aspose.slides/xpsoptions/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซทั้งหมดที่ใช้งาน:**  
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

จัดหาตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ XPS

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่แทนไฟล์งานนำเสนอ
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
>  // สร้างอ็อบเจ็กต์ Presentation ที่แทนไฟล์งานนำเสนอ
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

## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | คอนสตรัคเตอร์เริ่มต้น |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | ตั้งค่าเป็น true เพื่อแปลงไฟล์เมตาฟายล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | ตั้งค่าเป็น true เพื่อแปลงไฟล์เมตาฟายล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | ตั้งค่าเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์ |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | ตั้งค่าเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์ |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

คอนสตรัคเตอร์เริ่มต้น

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ ค่าเริ่มต้นคือ false

**คืนค่า:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ ค่าเริ่มต้นคือ false

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

ตั้งค่าเป็น true เพื่อแปลงไฟล์เมตาฟายล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. boolean แบบอ่าน/เขียน

--------------------

ค่าเริ่มต้นคือ **true**

**คืนค่า:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

ตั้งค่าเป็น true เพื่อแปลงไฟล์เมตาฟายล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. boolean แบบอ่าน/เขียน

--------------------

ค่าเริ่มต้นคือ **true**

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

ตั้งค่าเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. boolean แบบอ่าน/เขียน

--------------------

ค่าเริ่มต้นคือ **false**

**คืนค่า:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

ตั้งค่าเป็น true เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. boolean แบบอ่าน/เขียน

--------------------

ค่าเริ่มต้นคือ **false**

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |