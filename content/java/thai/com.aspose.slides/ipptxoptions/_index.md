---
title: IPptxOptions
second_title: Aspose.Slides สำหรับ Java – เอกสารอ้างอิง API
description: แสดงตัวเลือกสำหรับการบันทึกงานนำเสนอ OpenXml ในรูปแบบ PPTX, PPSX, POTX, PPTM, PPSM, POTM.
type: docs
url: /th/com.aspose.slides/ipptxoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

แสดงตัวเลือกสำหรับการบันทึกงานนำเสนอ OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM)  
## เมธอด

| Method | Description |
| --- | --- |
| [getConformance()](#getConformance--) | ระบุคลาสการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม |
| [setConformance(int value)](#setConformance-int-) | ระบุคลาสการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม |
| [getZip64Mode()](#getZip64Mode--) | ระบุว่าจะใช้รูปแบบ ZIP64 สำหรับเอกสาร Presentation หรือไม่ |
| [setZip64Mode(int value)](#setZip64Mode-int-) | ระบุว่าจะใช้รูปแบบ ZIP64 สำหรับเอกสาร Presentation หรือไม่ |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | ระบุว่าจะรีเฟรชภาพย่อของงานนำเสนอหรือไม่ |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | ระบุว่าจะรีเฟรชภาพย่อของงานนำเสนอหรือไม่ |
| [getCompressionLevel()](#getCompressionLevel--) | ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

ระบุคลาสการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม ค่าเริ่มต้นคือ [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**ผลลัพธ์:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

ระบุคลาสการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม ค่าเริ่มต้นคือ [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

ระบุว่าจะใช้รูปแบบ ZIP64 สำหรับเอกสาร Presentation หรือไม่ ค่าเริ่มต้นคือ [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract void setZip64Mode(int value)
```

ระบุว่าจะใช้รูปแบบ ZIP64 สำหรับเอกสาร Presentation หรือไม่ ค่าเริ่มต้นคือ [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```

ระบุว่าจะรีเฟรชภาพย่อของงานนำเสนอหรือไม่ บูลีนแบบอ่าน/เขียน ค่าเริ่มต้นคือ **true**.

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
public abstract void setRefreshThumbnail(boolean value)
```

ระบุว่าจะรีเฟรชภาพย่อของงานนำเสนอหรือไม่ บูลีนแบบอ่าน/เขียน ค่าเริ่มต้นคือ **true**.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ ค่าเริ่มต้นคือ [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

**ผลลัพธ์:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ ค่าเริ่มต้นคือ [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |