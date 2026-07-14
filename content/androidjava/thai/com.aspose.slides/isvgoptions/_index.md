---
title: ISVGOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงตัวเลือกของ SVG.
type: docs
url: /th/com.aspose.slides/isvgoptions/
---
**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

แสดงตัวเลือกของ SVG.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | กำหนดว่าข้อความบนสไลด์จะถูกบันทึกเป็นกราฟิกหรือไม่ |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | กำหนดว่าข้อความบนสไลด์จะถูกบันทึกเป็นกราฟิกหรือไม่ |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | คืนค่า หรือ ตั้งค่าขีดจำกัดความละเอียดต่ำสุดสำหรับการแรสเตอร์เมทาไฟล์ |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | คืนค่า หรือ ตั้งค่าขีดจำกัดความละเอียดต่ำสุดสำหรับการแรสเตอร์เมทาไฟล์ |
| [getDisable3DText()](#getDisable3DText--) | กำหนดว่าข้อความ 3D ถูกปิดใช้งานใน SVG หรือไม่ |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | กำหนดว่าข้อความ 3D ถูกปิดใช้งานใน SVG หรือไม่ |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | ปิดการแยกกราเดียน FromCornerX และ FromCenter |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | ปิดการแยกกราเดียน FromCornerX และ FromCenter |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 ไม่มีความสามารถในการกำหนดอินเซ็ตสำหรับมาร์คเกอร์ |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 ไม่มีความสามารถในการกำหนดอินเซ็ตสำหรับมาร์คเกอร์ |
| [getJpegQuality()](#getJpegQuality--) | กำหนดคุณภาพการเข้ารหัส JPEG |
| [setJpegQuality(int value)](#setJpegQuality-int-) | กำหนดคุณภาพการเข้ารหัส JPEG |
| [getShapeFormattingController()](#getShapeFormattingController--) | คืนค่าและตั้งค่าอินเทอร์เฟซคอลแบ็กที่อนุญาตให้ผู้ใช้ควบคุมการแปลงรูปทรง |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | คืนค่าและตั้งค่าอินเทอร์เฟซคอลแบ็กที่อนุญาตให้ผู้ใช้ควบคุมการแปลงรูปทรง |
| [getPicturesCompression()](#getPicturesCompression--) | แสดงระดับการบีบอัดรูปภาพ อ่าน/เขียน \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int) |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | แสดงระดับการบีบอัดรูปภาพ อ่าน/เขียน \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int) |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | แฟล็กบูลีนที่ระบุว่าพื้นที่ที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่ |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | แฟล็กบูลีนที่ระบุว่าพื้นที่ที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่ |
| [getUseFrameSize()](#getUseFrameSize--) | กำหนดว่ากรอบข้อความจะถูกรวมในพื้นที่การเรนเดอร์หรือไม่ |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | กำหนดว่ากรอบข้อความจะถูกรวมในพื้นที่การเรนเดอร์หรือไม่ |
| [getUseFrameRotation()](#getUseFrameRotation--) | กำหนดว่าจะทำการหมุนรูปทรงตามที่ระบุเมื่อเรนเดอร์หรือไม่ |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | กำหนดว่าจะทำการหมุนรูปทรงตามที่ระบุเมื่อเรนเดอร์หรือไม่ |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | กำหนดวิธีการจัดการกับฟอนต์ที่โหลดจากภายนอก |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | กำหนดวิธีการจัดการกับฟอนต์ที่โหลดจากภายนอก |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์ |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์ |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

กำหนดว่าข้อความบนสไลด์จะถูกบันทึกเป็นกราฟิกหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

กำหนดว่าข้อความบนสไลด์จะถูกบันทึกเป็นกราฟิกหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

คืนค่า หรือ ตั้งค่าขีดจำกัดความละเอียดต่ำสุดสำหรับการแรสเตอร์เมทาไฟล์ อ่าน/เขียน int.

**คืนค่า:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

คืนค่า หรือ ตั้งค่าขีดจำกัดความละเอียดต่ำสุดสำหรับการแรสเตอร์เมทาไฟล์ อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

กำหนดว่าข้อความ 3D ถูกปิดใช้งานใน SVG หรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

กำหนดว่าข้อความ 3D ถูกปิดใช้งานใน SVG หรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

ปิดการแยกกราเดียน FromCornerX และ FromCenter อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

ปิดการแยกกราเดียน FromCornerX และ FromCenter อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 ไม่มีความสามารถในการกำหนดอินเซ็ตสำหรับมาร์คเกอร์. Aspose.Slides SVG writing engine มีวิธีแก้ไขปัญหานี้: มันจะตัดส่วนปลายของเส้นที่มีลูกศร เพื่อให้เส้นไม่ทับมาร์คเกอร์. ตัวเลือกนี้จะปิดพฤติกรรมดังกล่าว. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 ไม่มีความสามารถในการกำหนดอินเซ็ตสำหรับมาร์คเกอร์. Aspose.Slides SVG writing engine มีวิธีแก้ไขปัญหานี้: มันจะตัดส่วนปลายของเส้นที่มีลูกศร เพื่อให้เส้นไม่ทับมาร์คเกอร์. ตัวเลือกนี้จะปิดพฤติกรรมดังกล่าว. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

กำหนดคุณภาพการเข้ารหัส JPEG อ่าน/เขียน int.

**คืนค่า:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

กำหนดคุณภาพการเข้ารหัส JPEG อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

คืนค่าและตั้งค่าอินเทอร์เฟซคอลแบ็กที่อนุญาตให้ผู้ใช้ควบคุมการแปลงรูปทรง อ่าน/เขียน [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**คืนค่า:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

คืนค่าและตั้งค่าอินเทอร์เฟซคอลแบ็กที่อนุญาตให้ผู้ใช้ควบคุมการแปลงรูปทรง อ่าน/เขียน [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

แสดงระดับการบีบอัดรูปภาพ อ่าน/เขียน \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**คืนค่า:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

แสดงระดับการบีบอัดรูปภาพ อ่าน/เขียน \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

แฟล็กบูลีนที่ระบุว่าพื้นที่ที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. ถ้าเป็น true พื้นที่ที่ถูกตัดจะถูกลบ, ถ้าเป็น false จะถูกจัดเก็บในเอกสาร (อาจทำให้ไฟล์ใหญ่ขึ้น) อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

แฟล็กบูลีนที่ระบุว่าพื้นที่ที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. ถ้าเป็น true พื้นที่ที่ถูกตัดจะถูกลบ, ถ้าเป็น false จะถูกจัดเก็บในเอกสาร (อาจทำให้ไฟล์ใหญ่ขึ้น) อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

กำหนดว่ากรอบข้อความจะถูกรวมในพื้นที่การเรนเดอร์หรือไม่. อ่าน/เขียน boolean. ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

กำหนดว่ากรอบข้อความจะถูกรวมในพื้นที่การเรนเดอร์หรือไม่. อ่าน/เขียน boolean. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

กำหนดว่าจะทำการหมุนรูปทรงตามที่ระบุเมื่อเรนเดอร์หรือไม่. อ่าน/เขียน boolean. ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

กำหนดว่าจะทำการหมุนรูปทรงตามที่ระบุเมื่อเรนเดอร์หรือไม่. อ่าน/เขียน boolean. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

กำหนดวิธีการจัดการกับฟอนต์ที่โหลดจากภายนอก อ่าน/เขียน [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**คืนค่า:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

กำหนดวิธีการจัดการกับฟอนต์ที่โหลดจากภายนอก อ่าน/เขียน [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์. เมื่อกำหนดเป็น true ลิเกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์. โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์. เมื่อกำหนดเป็น true ลิเกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์. โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |