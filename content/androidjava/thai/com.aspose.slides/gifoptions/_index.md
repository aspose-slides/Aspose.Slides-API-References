---
title: GifOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API อ้างอิง
description: แสดงตัวเลือกการส่งออก GIF.
type: docs
url: /th/com.aspose.slides/gifoptions/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
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
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // ขนาดของ GIF ที่ได้
>      gifOptions.setDefaultDelay(2000); // ระยะเวลาที่แต่ละสไลด์จะแสดงจนกว่าจะเปลี่ยนไปยังสไลด์ถัดไป
>      gifOptions.setTransitionFps(35); // เพิ่ม FPS เพื่อคุณภาพการเคลื่อนไหวการเปลี่ยนที่ดียิ่งขึ้น
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [GifOptions()](#GifOptions--) | สร้างอินสแตนซ์ใหม่ของคลาส GifOptions |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | รับหรือกำหนดขนาดเฟรม |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | รับหรือกำหนดขนาดเฟรม |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | กำหนดว่าการส่งออกสไลด์ที่ซ่อนอยู่จะทำหรือไม่ |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | กำหนดว่าการส่งออกสไลด์ที่ซ่อนอยู่จะทำหรือไม่ |
| [getTransitionFps()](#getTransitionFps--) | รับหรือกำหนดค่า FPS การเปลี่ยนแปลง [frames/sec] ค่าเริ่มต้นคือ 25 |
| [setTransitionFps(int value)](#setTransitionFps-int-) | รับหรือกำหนดค่า FPS การเปลี่ยนแปลง [frames/sec] ค่าเริ่มต้นคือ 25 |
| [getDefaultDelay()](#getDefaultDelay--) | รับหรือกำหนดเวลาหน่วงเวลาตั้งต้น [ms] |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | รับหรือกำหนดเวลาหน่วงเวลาตั้งต้น [ms] |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


สร้างอินสแตนซ์ใหม่ของคลาส GifOptions

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```


รับหรือกำหนดขนาดเฟรม

--------------------

หากขนาดว่างเปล่า ค่าจะถูกนำมาจาก [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**ค่าที่ส่งคืน:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```


รับหรือกำหนดขนาดเฟรม

--------------------

หากขนาดว่างเปล่า ค่าจะถูกนำมาจาก [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


กำหนดว่าการส่งออกสไลด์ที่ซ่อนอยู่จะทำหรือไม่ ค่าเริ่มต้นคือ false

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

**ค่าที่ส่งคืน:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


กำหนดว่าการส่งออกสไลด์ที่ซ่อนอยู่จะทำหรือไม่ ค่าเริ่มต้นคือ false

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


รับหรือกำหนดค่า FPS การเปลี่ยนแปลง [frames/sec] ค่าเริ่มต้นคือ 25

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

**ค่าที่ส่งคืน:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```


รับหรือกำหนดค่า FPS การเปลี่ยนแปลง [frames/sec] ค่าเริ่มต้นคือ 25

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


รับหรือกำหนดเวลาหน่วงเวลาตั้งต้น [ms] ค่านี้จะถูกใช้หาก [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) ไม่ได้ตั้งค่า ค่าเริ่มต้นคือ 1000

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

**ค่าที่ส่งคืน:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```


รับหรือกำหนดเวลาหน่วงเวลาตั้งต้น [ms] ค่านี้จะถูกใช้หาก [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) ไม่ได้ตั้งค่า ค่าเริ่มต้นคือ 1000

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