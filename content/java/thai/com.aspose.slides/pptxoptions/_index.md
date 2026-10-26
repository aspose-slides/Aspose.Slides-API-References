---
title: PptxOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวเลือกสำหรับการบันทึกงานนำเสนอ OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /th/com.aspose.slides/pptxoptions/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**ทั้งหมดของอินเทอร์เฟซที่ทำการ Implement:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

เป็นตัวเลือกสำหรับการบันทึกงานนำเสนอ OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | สร้างอินสแตนซ์ใหม่ของ PptxOptions |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getConformance()](#getConformance--) | ระบุคลาสความสอดคล้องที่เอกสาร Presentation ปฏิบัติตาม |
| [setConformance(int value)](#setConformance-int-) | ระบุคลาสความสอดคล้องที่เอกสาร Presentation ปฏิบัติตาม |
| [getZip64Mode()](#getZip64Mode--) | ระบุว่าใช้รูปแบบ ZIP64 กับเอกสาร Presentation หรือไม่ |
| [setZip64Mode(int value)](#setZip64Mode-int-) | ระบุว่าใช้รูปแบบ ZIP64 กับเอกสาร Presentation หรือไม่ |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | ระบุว่าภาพย่อของงานนำเสนอจะถูกรีเฟรชหรือไม่ |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | ระบุว่าภาพย่อของงานนำเสนอจะถูกรีเฟรชหรือไม่ |
| [getCompressionLevel()](#getCompressionLevel--) | ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสาร Presentation |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสาร Presentation |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

สร้างอินสแตนซ์ใหม่ของ PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

ระบุคลาสความสอดคล้องที่เอกสาร Presentation ปฏิบัติตาม ค่าปริยายคือ [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**คืนค่า:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

ระบุคลาสความสอดคล้องที่เอกสาร Presentation ปฏิบัติตาม ค่าปริยายคือ [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

ระบุว่าใช้รูปแบบ ZIP64 กับเอกสาร Presentation หรือไม่ ค่าเริ่มต้นคือ [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

ระบุว่าใช้รูปแบบ ZIP64 กับเอกสาร Presentation หรือไม่ ค่าเริ่มต้นคือ [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```

ระบุว่าภาพย่อของงานนำเสนอจะถูกรีเฟรชหรือไม่ อ่าน/เขียน แบบบูลีน ค่าเริ่มต้นคือ **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

เมื่อค่าตัวเลือกเป็น **true** thumbnail ใหม่จะถูกสร้างขึ้น

เมื่อค่าตัวเลือกเป็น **false** thumbnail ปัจจุบันจะถูกบันทึกตามเดิม

**คืนค่า:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

ระบุว่าภาพย่อของงานนำเสนอจะถูกรีเฟรชหรือไม่ อ่าน/เขียน แบบบูลีน ค่าเริ่มต้นคือ **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

เมื่อค่าตัวเลือกเป็น **bold** thumbnail ใหม่จะถูกสร้างขึ้น

เมื่อค่าตัวเลือกเป็น **false** thumbnail ปัจจุบันจะถูกบันทึกตามเดิม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสาร Presentation ค่าเริ่มต้นคือ [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ระดับการบีบอัดที่สูงกว่าจะทำให้ไฟล์มีขนาดเล็กลงแต่ต้องใช้เวลาประมวลผลมากขึ้น อัตราการบีบอัดจริงขึ้นอยู่กับเนื้อหาของงานนำเสนอ

**คืนค่า:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสาร Presentation ค่าเริ่มต้นคือ [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ระดับการบีบอัดที่สูงกว่าจะทำให้ไฟล์มีขนาดเล็กลงแต่ต้องใช้เวลาประมวลผลมากขึ้น อัตราการบีบอัดจริงขึ้นอยู่กับเนื้อหาของงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |