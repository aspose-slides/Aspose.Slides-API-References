---
title: SVGOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงตัวเลือก SVG.
type: docs
url: /th/com.aspose.slides/svgoptions/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**  
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable  
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Represents an SVG options.  
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions พร้อมระบุอ็อบเจกต์ตัวควบคุมการฝังลิงก์. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจกต์ Ink ในเอกสารที่ส่งออก. |
| [getUseFrameSize()](#getUseFrameSize--) | กำหนดว่าจะรวมกรอบข้อความในบริเวณการเรนเดอร์หรือไม่. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | กำหนดว่าจะรวมกรอบข้อความในบริเวณการเรนเดอร์หรือไม่. |
| [getUseFrameRotation()](#getUseFrameRotation--) | กำหนดว่าจะทำการหมุนรูปทรงตามที่ระบุขณะเรนเดอร์หรือไม่. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | กำหนดว่าจะทำการหมุนรูปทรงตามที่ระบุขณะเรนเดอร์หรือไม่. |
| [getVectorizeText()](#getVectorizeText--) | กำหนดว่าจะบันทึกข้อความบนสไลด์เป็นกราฟิกหรือไม่. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | กำหนดว่าจะบันทึกข้อความบนสไลด์เป็นกราฟิกหรือไม่. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | คืนค่า หรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์เมตาฟไฟล์. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | คืนค่า หรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์เมตาฟไฟล์. |
| [getDisable3DText()](#getDisable3DText--) | กำหนดว่าจะปิดการใช้งานข้อความ 3D ใน SVG หรือไม่. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | กำหนดว่าจะปิดการใช้งานข้อความ 3D ใน SVG หรือไม่. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | ปิดการแยกกราเดียนต์ FromCornerX และ FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | ปิดการแยกกราเดียนต์ FromCornerX และ FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 ไม่มีความสามารถในการกำหนดช่องว่างสำหรับมาร์คเกอร์. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 ไม่มีความสามารถในการกำหนดช่องว่างสำหรับมาร์คเกอร์. |
| [getDefault()](#getDefault--) | คืนค่าการตั้งค่าเริ่มต้น. |
| [getSimple()](#getSimple--) | คืนค่าการตั้งสําหรับการสร้างไฟล์ SVG ที่ง่ายที่สุดและเล็กที่สุด. |
| [getWYSIWYG()](#getWYSIWYG--) | คืนค่าการตั้งสําหรับการสร้างไฟล์ SVG ที่แม่นยำที่สุด. |
| [getJpegQuality()](#getJpegQuality--) | กำหนดคุณภาพการเข้ารหัส JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | กำหนดคุณภาพการเข้ารหัส JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | คืนค่าและกำหนดอินเทอร์เฟซคอลแบคที่อนุญาตให้ผู้ใช้ควบคุมการแปลงรูปทรง. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | คืนค่าและกำหนดอินเทอร์เฟซคอลแบคที่อนุญาตให้ผู้ใช้ควบคุมการแปลงรูปทรง. |
| [getPicturesCompression()](#getPicturesCompression--) | แสดงระดับการบีบอัดรูปภาพ |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | แสดงระดับการบีบอัดรูปภาพ |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | ฟลักบูลีนแสดงว่าตำแหน่งที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | ฟลักบูลีนแสดงว่าตำแหน่งที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions พร้อมระบุอ็อบเจกต์ตัวควบคุมการฝังลิงก์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | อ้างอิงตัวควบคุมการฝังลิงก์ |

--------------------

Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |
### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจกต์ Ink ในเอกสารที่ส่งออก. อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

กำหนดว่าจะรวมกรอบข้อความในบริเวณการเรนเดอร์หรือไม่. อ่าน/เขียน  boolean . ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

กำหนดว่าจะรวมกรอบข้อความในบริเวณการเรนเดอร์หรือไม่. อ่าน/เขียน  boolean . ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

กำหนดว่าจะทำการหมุนรูปทรงตามที่ระบุขณะเรนเดอร์หรือไม่. อ่าน/เขียน  boolean . ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

กำหนดว่าจะทำการหมุนรูปทรงตามที่ระบุขณะเรนเดอร์หรือไม่. อ่าน/เขียน  boolean . ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

กำหนดว่าจะบันทึกข้อความบนสไลด์เป็นกราฟิกหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

กำหนดว่าจะบันทึกข้อความบนสไลด์เป็นกราฟิกหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

คืนค่า หรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์เมตาฟไฟล์. อ่าน/เขียน int.

**คืนค่า:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

คืนค่า หรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์เมตาฟไฟล์. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

กำหนดว่าจะปิดการใช้งานข้อความ 3D ใน SVG หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

กำหนดว่าจะปิดการใช้งานข้อความ 3D ใน SVG หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

ปิดการแยกกราเดียนต์ FromCornerX และ FromCenter. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

ปิดการแยกกราเดียนต์ FromCornerX และ FromCenter. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

คืนค่าการตั้งค่าเริ่มต้น. อ่านอย่างเดียว [SVGOptions](../../com.aspose.slides/svgoptions).

**คืนค่า:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

คืนค่าการตั้งสําหรับการสร้างไฟล์ SVG ที่ง่ายที่สุดและเล็กที่สุด. อ่านอย่างเดียว [SVGOptions](../../com.aspose.slides/svgoptions).

**คืนค่า:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

คืนค่าการตั้งสําหรับการสร้างไฟล์ SVG ที่แม่นยำที่สุด. อ่านอย่างเดียว [SVGOptions](../../com.aspose.slides/svgoptions).

**คืนค่า:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

กำหนดคุณภาพการเข้ารหัส JPEG. อ่าน/เขียน int.

**คืนค่า:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

กำหนดคุณภาพการเข้ารหัส JPEG. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

คืนค่าและกำหนดอินเทอร์เฟซคอลแบคที่อนุญาตให้ผู้ใช้ควบคุมการแปลงรูปทรง. อ่าน/เขียน [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**คืนค่า:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

คืนค่าและกำหนดอินเทอร์เฟซคอลแบคที่อนุญาตให้ผู้ใช้ควบคุมการแปลงรูปทรง. อ่าน/เขียน [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

แสดงระดับการบีบอัดรูปภาพ

**คืนค่า:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

แสดงระดับการบีบอัดรูปภาพ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

ฟลักบูลีนแสดงว่าตำแหน่งที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. หากเป็น true จะลบส่วนที่ถูกตัดออก, หากเป็น false จะทำให้ส่วนที่ตัดอยู่ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น)

**คืนค่า:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

ฟลักบูลีนแสดงว่าตำแหน่งที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. หากเป็น true จะลบส่วนที่ถูกตัดออก, หากเป็น false จะทำให้ส่วนที่ตัดอยู่ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น)

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก. อ่าน/เขียน [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**คืนค่า:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก. อ่าน/เขียน [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์. เมื่อกำหนดเป็น true จะปิดการใช้ลิเกเจอร์ในผลลัพธ์ที่เรนเดอร์. ค่าเริ่มต้นคือ false.

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
public final void setDisableFontLigatures(boolean value)
```

รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์. เมื่อกำหนดเป็น true จะปิดการใช้ลิเกเจอร์ในผลลัพธ์ที่เรนเดอร์. ค่าเริ่มต้นคือ false.

--------------------

> ```
> ตัวอย่าง:
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