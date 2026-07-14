---
title: ITiffOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ TIFF.
type: docs
url: /th/com.aspose.slides/itiffoptions/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ TIFF.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getImageSize()](#getImageSize--) | ระบุขนาดของภาพ TIFF ที่สร้างขึ้น |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | ระบุขนาดของภาพ TIFF ที่สร้างขึ้น |
| [getDpiX()](#getDpiX--) | ระบุความละเอียดแนวนอนเป็นดอตต่ออินช์ |
| [setDpiX(long value)](#setDpiX-long-) | ระบุความละเอียดแนวนอนเป็นดอตต่ออินช์ |
| [getDpiY()](#getDpiY--) | ระบุความละเอียดแนวตั้งเป็นดอตต่ออินช์ |
| [setDpiY(long value)](#setDpiY-long-) | ระบุความละเอียดแนวตั้งเป็นดอตต่ออินช์ |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าหนังสือที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าหนังสือที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ |
| [getCompressionType()](#getCompressionType--) | ระบุประเภทการบีบอัด |
| [setCompressionType(int value)](#setCompressionType-int-) | ระบุประเภทการบีบอัด |
| [getPixelFormat()](#getPixelFormat--) | ระบุรูปแบบพิกเซลสำหรับภาพที่สร้างขึ้น |
| [setPixelFormat(int value)](#setPixelFormat-int-) | ระบุรูปแบบพิกเซลสำหรับภาพที่สร้างขึ้น |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดรูปแบบที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดรูปแบบที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [getBwConversionMode()](#getBwConversionMode--) | ระบุอัลกอริทึมสำหรับแปลงภาพสีให้เป็นภาพสีขาว-ดำ |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | ระบุอัลกอริทึมสำหรับแปลงภาพสีให้เป็นภาพสีขาว-ดำ |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจกต์ Ink ในเอกสารที่ส่งออก |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

ระบุขนาดของภาพ TIFF ที่สร้างขึ้น ค่าปริยายคือ 0x0 ซึ่งหมายความว่าขนาดภาพที่สร้างจะถูกคำนวณตามค่าขนาดของสไลด์งานนำเสนอ อ่าน/เขียน [Size](../../com.aspose.slides.android/size).

**คืนค่า:**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

ระบุขนาดของภาพ TIFF ที่สร้างขึ้น ค่าปริยายคือ 0x0 ซึ่งหมายความว่าขนาดภาพที่สร้างจะถูกคำนวณตามค่าขนาดของสไลด์งานนำเสนอ อ่าน/เขียน [Size](../../com.aspose.slides.android/size).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

ระบุความละเอียดแนวนอนเป็นดอตต่ออินช์ อ่าน/เขียน long.

**คืนค่า:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

ระบุความละเอียดแนวนอนเป็นดอตต่ออินช์ อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

ระบุความละเอียดแนวตั้งเป็นดอตต่ออินช์ อ่าน/เขียน long.

**คืนค่า:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

ระบุความละเอียดแนวตั้งเป็นดอตต่ออินช์ อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

ระบุว่าหนังสือที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

ระบุว่าหนังสือที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

ระบุรูปแบบพิกเซลสำหรับภาพที่สร้างขึ้น อ่าน/เขียน [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**คืนค่า:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

ระบุรูปแบบพิกเซลสำหรับภาพที่สร้างขึ้น อ่าน/เขียน [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดรูปแบบที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

รับหรือกำหนดรูปแบบที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

ระบุอัลกอริทึมสำหรับแปลงภาพสีให้เป็นภาพสีขาว-ดำ ตัวเลือกนี้จะใช้ได้เฉพาะเมื่อ CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) ตั้งค่าเป็น [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) หรือ [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) อ่าน/เขียน [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). ค่าเริ่มต้นคือ [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

ระบุอัลกอริทึมสำหรับแปลงภาพสีให้เป็นภาพสีขาว-ดำ ตัวเลือกนี้จะใช้ได้เฉพาะเมื่อ CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) ตั้งค่าเป็น [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) หรือ [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) อ่าน/เขียน [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). ค่าเริ่มต้นคือ [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจกต์ Ink ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)