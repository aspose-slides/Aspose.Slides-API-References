---
title: GifOptions
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงตัวเลือกการส่งออก GIF.
type: docs
url: /th/com.aspose.slides/gifoptions/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)  
```
public class GifOptions extends SaveOptions implements IGifOptions
```

แสดงตัวเลือกการส่งออก GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // ขนาดของ GIF ที่ได้ผลลัพธ์
>      gifOptions.setDefaultDelay(2000); // ระยะเวลาที่แต่ละสไลด์จะแสดงจนกว่าจะเปลี่ยนไปยังสไลด์ถัดไป
>      gifOptions.setTransitionFps(35); // เพิ่ม FPS เพื่อคุณภาพการเปลี่ยนภาพที่ดีขึ้น
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [GifOptions()](#GifOptions--) | สร้างอินสแตนซ์ใหม่ของคลาส GifOptions. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | ได้รับหรือกำหนดขนาดเฟรม. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | ได้รับหรือกำหนดขนาดเฟรม. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | กำหนดว่ารูปสไลด์ที่ซ่อนไว้จะถูกส่งออกหรือไม่. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | กำหนดว่ารูปสไลด์ที่ซ่อนไว้จะถูกส่งออกหรือไม่. |
| [getTransitionFps()](#getTransitionFps--) | ได้รับหรือกำหนดค่า FPS ของการเปลี่ยนภาพ [เฟรม/วินาที] ค่าเริ่มต้นคือ 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | ได้รับหรือกำหนดค่า FPS ของการเปลี่ยนภาพ [เฟรม/วินาที] ค่าเริ่มต้นคือ 25. |
| [getDefaultDelay()](#getDefaultDelay--) | ได้รับหรือกำหนดเวลาหน่วงเวลาตั้งต้น [มิลลิวินาที]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | ได้รับหรือกำหนดเวลาหน่วงเวลาตั้งต้น [มิลลิวินาที]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

สร้างอินสแตนซ์ใหม่ของคลาส GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```

ได้รับหรือกำหนดขนาดเฟรม.

--------------------

หากขนาดว่างเปล่า จะใช้ค่าจาก [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**คืนค่า:**  
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```

ได้รับหรือกำหนดขนาดเฟรม.

--------------------

หากขนาดว่างเปล่า จะใช้ค่าจาก [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

กำหนดว่ารูปสไลด์ที่ซ่อนไว้จะถูกส่งออกหรือไม่ ค่าเริ่มต้นคือ false.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**  
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

กำหนดว่ารูปสไลด์ที่ซ่อนไว้จะถูกส่งออกหรือไม่ ค่าเริ่มต้นคือ false.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

ได้รับหรือกำหนดค่า FPS ของการเปลี่ยนภาพ [เฟรม/วินาที] ค่าเริ่มต้นคือ 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**  
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

ได้รับหรือกำหนดค่า FPS ของการเปลี่ยนภาพ [เฟรม/วินาที] ค่าเริ่มต้นคือ 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

ได้รับหรือกำหนดเวลาหน่วงเวลาตั้งต้น [มิลลิวินาที] ค่านี้จะใช้หาก [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) ไม่ได้ตั้งค่า ค่าเริ่มต้นคือ 1000.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**  
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

ได้รับหรือกำหนดเวลาหน่วงเวลาตั้งต้น [มิลลิวินาที] ค่านี้จะใช้หาก [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) ไม่ได้ตั้งค่า ค่าเริ่มต้นคือ 1000.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |