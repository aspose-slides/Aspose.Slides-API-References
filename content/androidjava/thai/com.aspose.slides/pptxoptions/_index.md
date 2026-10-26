---
title: PptxOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวเลือกสำหรับการบันทึกงานนำเสนอ OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
type: docs
url: /th/com.aspose.slides/pptxoptions/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

เป็นตัวเลือกสำหรับการบันทึกงานนำเสนอ OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM)。
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | สร้างอินสแตนซ์ใหม่ของ PptxOptions |
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getConformance()](#getConformance--) | ระบุคลาสการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม |
| [setConformance(int value)](#setConformance-int-) | ระบุคลาสการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม |
| [getZip64Mode()](#getZip64Mode--) | ระบุว่าราฟอร์แมต ZIP64 ถูกใช้สำหรับเอกสาร Presentation หรือไม่ |
| [setZip64Mode(int value)](#setZip64Mode-int-) | ระบุว่าราฟอร์แมต ZIP64 ถูกใช้สำหรับเอกสาร Presentation หรือไม่ |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | ระบุว่าจะรีเฟรช thumbnail ของ presentation หรือไม่ |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | ระบุว่าจะรีเฟรช thumbnail ของ presentation หรือไม่ |
| [getCompressionLevel()](#getCompressionLevel--) | ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสาร presentation |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสาร presentation |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


สร้างอินสแตนซ์ใหม่ของ PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```


ระบุคลาสการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม ค่าปริยายคือ [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**ผลลัพธ์:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


ระบุคลาสการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม ค่าปริยายคือ [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```


ระบุว่าราฟอร์แมต ZIP64 ถูกใช้สำหรับเอกสาร Presentation หรือไม่ ค่าปริยายคือ [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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


**ผลลัพธ์:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```


ระบุว่าราฟอร์แมต ZIP64 ถูกใช้สำหรับเอกสาร Presentation หรือไม่ ค่าปริยายคือ [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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


ระบุว่าภาพย่อของ presentation จะถูกรีเฟรชหรือไม่ อ่าน/เขียน เป็นบูลีน ค่าปริยายคือ **true**.

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

เมื่อค่าตัวเลือกเป็น **true** ภาพย่อใหม่จะถูกสร้างขึ้น

เมื่อค่าตัวเลือกเป็น **false** ภาพย่อปัจจุบันจะถูกบันทึกตามเดิม

**ผลลัพธ์:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```


ระบุว่าภาพย่อของ presentation จะถูกรีเฟชหรือไม่ อ่าน/เขียน เป็นบูลีน ค่าปริยายคือ **true**.

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

เมื่อค่าตัวเลือกเป็น **true** ภาพย่อใหม่จะถูกสร้างขึ้น

เมื่อค่าตัวเลือกเป็น **false** ภาพย่อปัจจุบันจะถูกบันทึกตามเดิม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสาร presentation ค่าปริยายคือ [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> ตัวอย่าง:
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

ระดับการบีบอัดที่สูงขึ้นจะทำให้ไฟล์เล็กลง แต่ต้องใช้เวลาประมวลผลมากขึ้น อัตราการบีบอัดจริงขึ้นอยู่กับเนื้อหาของ presentation

**ผลลัพธ์:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสาร presentation ค่าปริยายคือ [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

ระดับการบีบอัดที่สูงขึ้นจะทำให้ไฟล์เล็กลง แต่ต้องใช้เวลาประมวลผลมากขึ้น อัตราการบีบอัดจริงขึ้นอยู่กับเนื้อหาของ presentation

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |