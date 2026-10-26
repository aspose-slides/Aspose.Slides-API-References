---
title: TiffOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ TIFF.
type: docs
url: /th/com.aspose.slides/tiffoptions/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่แทนไฟล์การนำเสนอ
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // กำลังบันทึกการนำเสนอเป็นเอกสาร TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่แทนไฟล์ Presentation
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // สร้างอินสแตนซ์ของคลาส TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // ตั้งค่าชนิดการบีบอัด
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // ชนิดการบีบอัด
>      // Default - ระบุโครงร่างการบีบอัดเริ่มต้น (LZW).
>      // None - ระบุว่าไม่มีการบีบอัด
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // ความลึกขึ้นอยู่กับชนิดการบีบอัดและไม่สามารถตั้งค่าได้ด้วยตนเอง
>      // หน่วยความละเอียดจะเท่ากับ 2 (จุดต่อ นิ้ว) เสมอ
>      // ตั้งค่า DPI ของภาพ
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // ตั้งค่าขนาดภาพ
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // บันทึกการนำเสนอเป็น TIFF ด้วยขนาดภาพที่กำหนด
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่แทนไฟล์ Presentation
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      // ImagePixelFormat มีค่าต่อไปนี้ (ตามที่เห็นจากเอกสาร):
>      //Format1bppIndexed; // 1 บิตต่อพิกเซล, แบบจัดทำดัชนี.
>      //Format4bppIndexed; // 4 บิตต่อพิกเซล, แบบจัดทำดัชนี.
>      //Format8bppIndexed; // 8 บิตต่อพิกเซล, แบบจัดทำดัชนี.
>      //Format24bppRgb; // 24 บิตต่อพิกเซล, RGB.
>      //Format32bppArgb; // 32 บิตต่อพิกเซล, ARGB.
> 
>      // บันทึกการนำเสนอเป็น TIFF ด้วยขนาดภาพที่กำหนด
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | คอนสตรัคเตอร์เริ่มต้น. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าต้องการให้เอกสารที่สร้างรวมสไลด์ที่ซ่อนไว้หรือไม่. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าต้องการให้เอกสารที่สร้างรวมสไลด์ที่ซ่อนไว้หรือไม่. |
| [getImageSize()](#getImageSize--) | ระบุขนาดของภาพ TIFF ที่สร้าง. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | ระบุขนาดของภาพ TIFF ที่สร้าง. |
| [getDpiX()](#getDpiX--) | ระบุความละเอียดแนวนอนเป็นจุดต่อ นิ้ว. |
| [setDpiX(long value)](#setDpiX-long-) | ระบุความละเอียดแนวนอนเป็นจุดต่อ นิ้ว. |
| [getDpiY()](#getDpiY--) | ระบุความละเอียดแนวตั้งเป็นจุดต่อ นิ้ว. |
| [setDpiY(long value)](#setDpiY-long-) | ระบุความละเอียดแนวตั้งเป็นจุดต่อ นิ้ว. |
| [getCompressionType()](#getCompressionType--) | ระบุประเภทการบีบอัด. |
| [setCompressionType(int value)](#setCompressionType-int-) | ระบุประเภทการบีบอัด. |
| [getPixelFormat()](#getPixelFormat--) | ระบุรูปแบบพิกเซลสำหรับภาพที่สร้าง. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | ระบุรูปแบบพิกเซลสำหรับภาพที่สร้าง. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์วางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์วางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | ระบุอัลกอริธึมสำหรับแปลงภาพสีเป็นภาพขาวดำ. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | ระบุอัลกอริธึมสำหรับแปลงภาพสีเป็นภาพขาวดำ. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

คอนสตรัคเตอร์เริ่มต้น.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**ผลลัพธ์:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

ระบุว่าต้องการให้เอกสารที่สร้างรวมสไลด์ที่ซ่อนไว้หรือไม่. ค่าเริ่มต้นคือ false.

**ผลลัพธ์:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

ระบุว่าต้องการให้เอกสารที่สร้างรวมสไลด์ที่ซ่อนไว้หรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```

ระบุขนาดของภาพ TIFF ที่สร้าง. ค่าเริ่มต้นคือ 0x0 ซึ่งหมายความว่าขนาดภาพที่สร้างจะคำนวณตามขนาดสไลด์ของการนำเสนอ. อ่าน/เขียน [Size](../../com.aspose.slides.android/size).

**ผลลัพธ์:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```

ระบุขนาดของภาพ TIFF ที่สร้าง. ค่าเริ่มต้นคือ 0x0 ซึ่งหมายความว่าขนาดภาพที่สร้างจะคำนวณตามขนาดสไลด์ของการนำเสนอ. อ่าน/เขียน [Size](../../com.aspose.slides.android/size).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

ระบุความละเอียดแนวนอนเป็นจุดต่อ นิ้ว. อ่าน/เขียน long.

**ผลลัพธ์:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

ระบุความละเอียดแนวนอนเป็นจุดต่อ นิ้ว. อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

ระบุความละเอียดแนวตั้งเป็นจุดต่อ นิ้ว. อ่าน/เขียน long.

**ผลลัพธ์:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

ระบุความละเอียดแนวตั้งเป็นจุดต่อ นิ้ว. อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

ระบุประเภทการบีบอัด. อ่าน/เขียน [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**ผลลัพธ์:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

ระบุประเภทการบีบอัด. อ่าน/เขียน [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

ระบุรูปแบบพิกเซลสำหรับภาพที่สร้าง. อ่าน/เขียน [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**ผลลัพธ์:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

ระบุรูปแบบพิกเซลสำหรับภาพที่สร้าง. อ่าน/เขียน [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์วางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

รับหรือกำหนดโหมดที่สไลด์วางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

ระบุอัลกอริธึมสำหรับแปลงภาพสีเป็นภาพขาวดำ. ตัวเลือกนี้จะถูกนำไปใช้เฉพาะเมื่อ CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) ตั้งเป็น [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) หรือ [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) อ่าน/เขียน [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). ค่าเริ่มต้นคือ [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**ผลลัพธ์:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```

ระบุอัลกอริธึมสำหรับแปลงภาพสีเป็นภาพขาวดำ. ตัวเลือกนี้จะถูกนำไปใช้เฉพาะเมื่อ CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) ตั้งเป็น [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) หรือ [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) อ่าน/เขียน [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). ค่าเริ่มต้นคือ [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |