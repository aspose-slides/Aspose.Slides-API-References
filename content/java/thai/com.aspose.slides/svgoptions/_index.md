---
title: SVGOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของตัวเลือก SVG
type: docs
url: /th/com.aspose.slides/svgoptions/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable  
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

แสดงตัวเลือก SVG.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | รายละเอียด |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions โดยระบุวัตถุ link embedding controller |

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของวัตถุ Ink ในเอกสารที่ส่งออก |
| [getUseFrameSize()](#getUseFrameSize--) | กำหนดว่าจะรวมกรอบข้อความในพื้นที่แสดงผลหรือไม่ |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | กำหนดว่าจะรวมกรอบข้อความในพื้นที่แสดงผลหรือไม่ |
| [getUseFrameRotation()](#getUseFrameRotation--) | กำหนดว่าจะทำการหมุนรูปร่างตามที่ระบุเมื่อแสดงผลหรือไม่ |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | กำหนดว่าจะทำการหมุนรูปร่างตามที่ระบุเมื่อแสดงผลหรือไม่ |
| [getVectorizeText()](#getVectorizeText--) | กำหนดว่าจะบันทึกข้อความบนสไลด์เป็นกราฟิกหรือไม่ |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | กำหนดว่าจะบันทึกข้อความบนสไลด์เป็นกราฟิกหรือไม่ |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | คืนค่าหรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์ metafile |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | คืนค่าหรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์ metafile |
| [getDisable3DText()](#getDisable3DText--) | กำหนดว่าจะปิดการใช้งานข้อความ 3D ใน SVG หรือไม่ |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | กำหนดว่าจะปิดการใช้งานข้อความ 3D ใน SVG หรือไม่ |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | ปิดการแยก gradient FromCornerX และ FromCenter |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | ปิดการแยก gradient FromCornerX และ FromCenter |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 ขาดความสามารถในการกำหนด inset สำหรับ markers |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 ขาดความสามารถในการกำหนด inset สำหรับ markers |
| [getDefault()](#getDefault--) | คืนค่าการตั้งค่าเริ่มต้น |
| [getSimple()](#getSimple--) | คืนค่าการตั้งค่าสำหรับการสร้างไฟล์ SVG ที่เรียบง่ายและขนาดเล็กที่สุด |
| [getWYSIWYG()](#getWYSIWYG--) | คืนค่าการตั้งสําหรับการสร้างไฟล์ SVG ที่แม่นยำที่สุด |
| [getJpegQuality()](#getJpegQuality--) | กำหนดคุณภาพการเข้ารหัส JPEG |
| [setJpegQuality(int value)](#setJpegQuality-int-) | กำหนดคุณภาพการเข้ารหัส JPEG |
| [getShapeFormattingController()](#getShapeFormattingController--) | คืนค่าและกำหนดอินเทอร์เฟซ callback ที่ให้ผู้ใช้ควบคุมการแปลงรูปร่าง |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | คืนค่าและกำหนดอินเทอร์เฟซ callback ที่ให้ผู้ใช้ควบคุมการแปลงรูปร่าง |
| [getPicturesCompression()](#getPicturesCompression--) | แสดงระดับการบีบอัดรูปภาพ |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | แสดงระดับการบีบอัดรูปภาพ |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | แฟล็กบูลีนบ่งชี้ว่าตำแหน่งที่ถูกครอปยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่ |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | แฟล็กบูลีนบ่งชี้ว่าตำแหน่งที่ถูกครอปยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่ |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ ligatures |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ ligatures |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions โดยระบุวัตถุ link embedding controller

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | อ้างอิงตัวควบคุมการฝังลิงก์ |

--------------------

Link embedding controller เป็นอ็อบเจ็กต์ delegate ที่รับผิดชอบการตัดสินใจว่าทรัพยากร (เช่น รูปภาพ) จำเป็นต้องฝังหรืออ้างอิงเป็นทรัพยากรภายนอกหรือไม่

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของวัตถุ Ink ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

กำหนดว่าจะรวมกรอบข้อความในพื้นที่แสดงผลหรือไม่ อ่าน/เขียน  boolean . ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

กำหนดว่าจะรวมกรอบข้อความในพื้นที่แสดงผลหรือไม่ อ่าน/เขียน  boolean . ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

กำหนดว่าจะทำการหมุนรูปร่างตามที่ระบุเมื่อแสดงผลหรือไม่ อ่าน/เขียน  boolean . ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

กำหนดว่าจะทำการหมุนรูปร่างตามที่ระบุเมื่อแสดงผลหรือไม่ อ่าน/เขียน  boolean . ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

กำหนดว่าจะบันทึกข้อความบนสไลด์เป็นกราฟิกหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

กำหนดว่าจะบันทึกข้อความบนสไลด์เป็นกราฟิกหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

คืนค่าหรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์ metafile อ่าน/เขียน int.

**คืนค่า:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

คืนค่าหรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์ metafile อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

กำหนดว่าจะปิดการใช้งานข้อความ 3D ใน SVG หรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

กำหนดว่าจะปิดการใช้งานข้อความ 3D ใน SVG หรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

ปิดการแยก gradient FromCornerX และ FromCenter อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

ปิดการแยก gradient FromCornerX และ FromCenter อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 ขาดความสามารถในการกำหนด inset สำหรับ markers. Aspose.Slides SVG writing engine มีวิธีแก้ปัญหานี้: มันครอบส่วนสุดของเส้นพร้อมลูกศร เพื่อให้เส้นไม่ทับ markers. ตัวเลือกนี้ปิดพฤติกรรมดังกล่าว อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 ขาดความสามารถในการกำหนด inset สำหรับ markers. Aspose.Slides SVG writing engine มีวิธีแก้ปัญหานี้: มันครอบส่วนสุดของเส้นพร้อมลูกศร เพื่อให้เส้นไม่ทับ markers. ตัวเลือกนี้ปิดพฤติกรรมดังกล่าว อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

คืนค่าการตั้งค่าเริ่มต้น อ่านอย่างเดียว [SVGOptions](../../com.aspose.slides/svgoptions).

**คืนค่า:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

คืนค่าการตั้งค่าสำหรับการสร้างไฟล์ SVG ที่เรียบง่ายและขนาดเล็กที่สุด อ่านอย่างเดียว [SVGOptions](../../com.aspose.slides/svgoptions).

**คืนค่า:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

คืนค่าการตั้งสําหสำหรับการสร้างไฟล์ SVG ที่แม่นยำที่สุด อ่านอย่างเดียว [SVGOptions](../../com.aspose.slides/svgoptions).

**คืนค่า:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

กำหนดคุณภาพการเข้ารหัส JPEG อ่าน/เขียน int.

**คืนค่า:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

กำหนดคุณภาพการเข้ารหัส JPEG อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

คืนค่าและกำหนดอินเทอร์เฟซ callback ที่ให้ผู้ใช้ควบคุมการแปลงรูปร่าง อ่าน/เขียน [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**คืนค่า:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

คืนค่าและกำหนดอินเทอร์เฟซ callback ที่ให้ผู้ใช้ควบคุมการแปลงรูปร่าง อ่าน/เขียน [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
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
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

แฟล็กบูลีนบ่งชี้ว่าตำแหน่งที่ถูกครอปยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่ หากเป็น true ตำแหน่งที่ถูกครอปจะถูกลบ หากเป็น false จะถูกจัดเก็บในเอกสาร (อาจทำให้ไฟล์ใหญ่ขึ้น)

**คืนค่า:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

แฟล็กบูลีนบ่งชี้ว่าตำแหน่งที่ถูกครอปยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่ หากเป็น true ตำแหน่งที่ถูกครอปจะถูกลบ หากเป็น false จะถูกจัดเก็บในเอกสาร (อาจทำให้ไฟล์ใหญ่ขึ้น)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก อ่าน/เขียน [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**คืนค่า:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก อ่าน/เขียน [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ ligatures. เมื่อกำหนดเป็น true จะปิดการใช้ ligatures ในผลลัพธ์ที่เรนเดอร์. ค่าเริ่มต้นคือ false.

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

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ ligatures. เมื่อกำหนดเป็น true จะปิดการใช้ ligatures ในผลลัพธ์ที่เรนเดอร์. ค่าเริ่มต้นคือ false.

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
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |