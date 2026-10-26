---
title: IPptxOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงตัวเลือกสำหรับการบันทึกงานนำเสนอ OpenXml ประเภท PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /th/com.aspose.slides/ipptxoptions/
---
**อินเทอร์เฟซที่ทำตามทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

แสดงตัวเลือกสำหรับการบันทึกงานนำเสนอ OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getConformance()](#getConformance--) | ระบุระดับการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม |
| [setConformance(int value)](#setConformance-int-) | ระบุระดับการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม |
| [getZip64Mode()](#getZip64Mode--) | ระบุว่ารูปแบบ ZIP64 ถูกใช้สำหรับเอกสาร Presentation หรือไม่ |
| [setZip64Mode(int value)](#setZip64Mode-int-) | ระบุว่ารูปแบบ ZIP64 ถูกใช้สำหรับเอกสาร Presentation หรือไม่ |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | ระบุว่าภาพขนาดย่อของงานนำเสนอจะถูกรีเฟรชหรือไม่ |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | ระบุว่าภาพขนาดย่อของงานนำเสนอจะถูกรีเฟรชหรือไม่ |
| [getCompressionLevel()](#getCompressionLevel--) | ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ |

### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

ระบุระดับการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม ค่าดีฟอลต์คือ [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**คืนค่า:**
int

### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

ระบุระดับการปฏิบัติตามที่เอกสาร Presentation ปฏิบัติตาม ค่าดีฟอลต์คือ [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

ระบุว่ารูปแบบ ZIP64 ถูกใช้สำหรับเอกสาร Presentation หรือไม่ ค่าดีฟอลต์คือ [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract void setZip64Mode(int value)
```

ระบุว่ารูปแบบ ZIP64 ถูกใช้สำหรับเอกสาร Presentation หรือไม่ ค่าดีฟอลต์คือ [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract boolean getRefreshThumbnail()
```

ระบุว่าภาพขนาดย่อของงานนำเสนอจะถูกรีเฟรชหรือไม่ อ่าน/เขียน บูลีน ค่าดีฟอลต์คือ **true**.

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

เมื่อค่าตัวเลือกเป็น **true** จะมีการสร้างภาพขนาดย่อใหม่

เมื่อค่าตัวเลือกเป็น **false** ภาพขนาดย่อปัจจุบันจะถูกบันทึกไว้ตามเดิม

**คืนค่า:**
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

ระบุว่าภาพขนาดย่อของงานนำเสนอจะถูกรีเฟรชหรือไม่ อ่าน/เขียน บูลีน ค่าดีฟอลต์คือ **true**.

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

เมื่อค่าตัวเลือกเป็น **true** จะมีการสร้างภาพขนาดย่อใหม่

เมื่อค่าตัวเลือกเป็น **false** ภาพขนาดย่อปัจจุบันจะถูกบันทึกไว้ตามเดิม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ ค่าดีฟอลต์คือ [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

ระดับการบีบอัดที่สูงกว่าจะทำให้ไฟล์มีขนาดเล็กลงแต่ต้องใช้เวลาในการประมวลผลมากขึ้น อัตราการบีบอัดจริงขึ้นอยู่กับเนื้อหาของงานนำเสนอ

**คืนค่า:**
int

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

ระบุระดับการบีบอัดที่ใช้เมื่อบันทึกเอกสารงานนำเสนอ ค่าดีฟอลต์คือ [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

ระดับการบีบอัดที่สูงกว่าจะทำให้ไฟล์มีขนาดเล็กลงแต่ต้องใช้เวลาในการประมวลผลมากขึ้น อัตราการบีบอัดจริงขึ้นอยู่กับเนื้อหาของงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |