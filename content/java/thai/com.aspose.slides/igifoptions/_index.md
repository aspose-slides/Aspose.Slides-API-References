---
title: IGifOptions
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงตัวเลือกการส่งออก GIF.
type: docs
url: /th/com.aspose.slides/igifoptions/
---
**ส่วนติดต่อที่ใช้งานทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

แสดงตัวเลือกการส่งออก GIF.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | รับหรือกำหนดขนาดเฟรม. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | รับหรือกำหนดขนาดเฟรม. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่. |
| [getTransitionFps()](#getTransitionFps--) | รับหรือกำหนดค่า FPS ของการเปลี่ยนภาพ [เฟรมต่อวินาที] ค่าเริ่มต้นคือ 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | รับหรือกำหนดค่า FPS ของการเปลี่ยนภาพ [เฟรมต่อวินาที] ค่าเริ่มต้นคือ 25. |
| [getDefaultDelay()](#getDefaultDelay--) | รับหรือกำหนดเวลาหน่วงอัตราเริ่มต้น [มิลลิวินาที]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | รับหรือกำหนดเวลาหน่วงอัตราเริ่มต้น [มิลลิวินาที]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```


รับหรือกำหนดขนาดเฟรม.

--------------------

หากขนาดว่างเปล่า ค่าจะถูกนำมาจาก [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**คืนค่า:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```


รับหรือกำหนดขนาดเฟรม.

--------------------

หากขนาดว่างเปล่า ค่าจะถูกนำมาจาก [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่ ค่าเริ่มต้นคือ false.

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
public abstract void setExportHiddenSlides(boolean value)
```


กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่ ค่าเริ่มต้นคือ false.

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
public abstract int getTransitionFps()
```


รับหรือกำหนดค่า FPS ของการเปลี่ยนภาพ [เฟรมต่อวินาที] ค่าเริ่มต้นคือ 25.

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
public abstract void setTransitionFps(int value)
```


รับหรือกำหนดค่า FPS ของการเปลี่ยนภาพ [เฟรมต่อวินาที] ค่าเริ่มต้นคือ 25.

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
public abstract int getDefaultDelay()
```


รับหรือกำหนดเวลาหน่วงอัตราเริ่มต้น [มิลลิวินาที] ค่าดังกล่าวจะถูกใช้หาก [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) ไม่ได้ตั้งค่า ค่าเริ่มต้นคือ 1000.

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
public abstract void setDefaultDelay(int value)
```


รับหรือกำหนดเวลาหน่วงอัตราเริ่มต้น [มิลลิวินาที] ค่าดังกล่าวจะถูกใช้หาก [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) ไม่ได้ตั้งค่า ค่าเริ่มต้นคือ 1000.

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