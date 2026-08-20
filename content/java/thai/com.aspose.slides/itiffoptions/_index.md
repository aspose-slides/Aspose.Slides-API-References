---
title: ITiffOptions
second_title: Aspose.Slides สำหรับ Java API Reference
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ TIFF.
type: docs
url: /th/com.aspose.slides/itiffoptions/
---
**ทั้งหมดที่ใช้งานอินเทอร์เฟซ:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอเป็นรูปแบบ TIFF.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getImageSize()](#getImageSize--) | ระบุขนาดของภาพ TIFF ที่สร้างขึ้น |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | ระบุขนาดของภาพ TIFF ที่สร้างขึ้น |
| [getDpiX()](#getDpiX--) | ระบุความละเอียดเชิงแนวนอนเป็นจุดต่ออินช์ |
| [setDpiX(long value)](#setDpiX-long-) | ระบุความละเอียดเชิงแนวนอนเป็นจุดต่ออินช์ |
| [getDpiY()](#getDpiY--) | ระบุความละเอียดเชิงตั้งเป็นจุดต่ออินช์ |
| [setDpiY(long value)](#setDpiY-long-) | ระบุความละเอียดเชิงตั้งเป็นจุดต่ออินช์ |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ |
| [getCompressionType()](#getCompressionType--) | ระบุประเภทการบีบอัด |
| [setCompressionType(int value)](#setCompressionType-int-) | ระบุประเภทการบีบอัด |
| [getPixelFormat()](#getPixelFormat--) | ระบุฟอร์แมตพิกเซลสำหรับภาพที่สร้าง |
| [setPixelFormat(int value)](#setPixelFormat-int-) | ระบุฟอร์แมตพิกเซลสำหรับภาพที่สร้าง |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดการวางสไลด์บนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดการวางสไลด์บนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [getBwConversionMode()](#getBwConversionMode--) | ระบุอัลกอริธึมสำหรับแปลงภาพสีเป็นภาพขาวดำ |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | ระบุอัลกอริธึมสำหรับแปลงภาพสีเป็นภาพขาวดำ |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของวัตถุ Ink ในเอกสารที่ส่งออก |

### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```

ระบุขนาดของภาพ TIFF ที่สร้างขึ้น ค่าตั้งต้นคือ 0x0 ซึ่งหมายความว่าขนาดของภาพที่สร้างจะคำนวณจากค่าขนาดสไลด์ของการนำเสนอ อ่าน/เขียน java.awt.Dimension.

**คืนค่า:**
java.awt.Dimension

### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```

ระบุขนาดของภาพ TIFF ที่สร้างขึ้น ค่าตั้งต้นคือ 0x0 ซึ่งหมายความว่าขนาดของภาพที่สร้างจะคำนวณจากค่าขนาดสไลด์ของการนำเสนอ อ่าน/เขียน java.awt.Dimension.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

ระบุความละเอียดเชิงแนวนอนเป็นจุดต่ออินช์ อ่าน/เขียน long.

**คืนค่า:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

ระบุความละเอียดเชิงแนวนอนเป็นจุดต่ออินช์ อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

ระบุความละเอียดเชิงตั้งเป็นจุดต่ออินช์ อ่าน/เขียน long.

**คืนค่า:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

ระบุความละเอียดเชิงตั้งเป็นจุดต่ออินช์ อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

ระบุประเภทการบีบอัด อ่าน/เขียน [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**คืนค่า:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

ระบุประเภทการบีบอัด อ่าน/เขียน [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

ระบุฟอร์แมตพิกเซลสำหรับภาพที่สร้าง อ่าน/เขียน [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**คืนค่า:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

ระบุฟอร์แมตพิกเซลสำหรับภาพที่สร้าง อ่าน/เขียน [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดการวางสไลด์บนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**คืนค่า:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

รับหรือกำหนดโหมดการวางสไลด์บนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract int getBwConversionMode()
```

ระบุอัลกอริธึมสำหรับแปลงภาพสีเป็นภาพขาวดำ ตัวเลือกนี้จะใช้ได้เฉพาะเมื่อ CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) ถูกตั้งค่าเป็น [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) หรือ [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) อ่าน/เขียน [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode) ค่าเริ่มต้นคือ [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**คืนค่า:**
int

### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

ระบุอัลกอริธึมสำหรับแปลงภาพสีเป็นภาพขาวดำ ตัวเลือกนี้จะใช้ได้เฉพาะเมื่อ CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) ถูกตั้งค่าเป็น [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) หรือ [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) อ่าน/เขียน [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode) ค่าเริ่มต้นคือ [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของวัตถุ Ink ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)