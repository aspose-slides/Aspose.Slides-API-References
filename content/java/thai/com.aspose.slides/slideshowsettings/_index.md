---
title: SlideShowSettings
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงการตั้งค่าการแสดงสไลด์สำหรับงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/slideshowsettings/
---
**การสืบทอด:**
java.lang.Object
```
public class SlideShowSettings
```

แสดงการตั้งค่าโหมดการแสดงสไลด์สำหรับงานนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | รับหรือกำหนดประเภทการแสดงสไลด์ |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | รับหรือกำหนดประเภทการแสดงสไลด์ |
| [getLoop()](#getLoop--) | วนซ้ำสไลด์โชว์ |
| [setLoop(boolean value)](#setLoop-boolean-) | วนซ้ำสไลด์โชว์ |
| [getShowNarration()](#getShowNarration--) | แสดงคำบรรยายในการแสดงสไลด์ |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | แสดงคำบรรยายในการแสดงสไลด์ |
| [getShowAnimation()](#getShowAnimation--) | แสดงแอนิเมชันในการแสดงสไลด์ |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | แสดงแอนิเมชันในการแสดงสไลด์ |
| [getPenColor()](#getPenColor--) | สีปากกาสำหรับการแสดงสไลด์ |
| [getSlides()](#getSlides--) | ช่วงสไลด์ |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | ช่วงสไลด์ |
| [getUseTimings()](#getUseTimings--) | ใช้จังหวะในการแสดงสไลด์ |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | ใช้จังหวะในการแสดงสไลด์ |
| [getShowMediaControls()](#getShowMediaControls--) | แสดงการควบคุมสื่อ |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | แสดงการควบคุมสื่อ |

### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

รับหรือกำหนดประเภทการแสดงสไลด์ แสดงโดย SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) บรรพบุรุษ: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) และ [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // ตั้งค่าเป็นประเภท "Browsed at a kiosk (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // ตั้งค่าเป็นประเภท "Browsed by individual (window)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // ตั้งค่าเป็นประเภท "Presented by a speaker (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

รับหรือกำหนดประเภทการแสดงสไลด์ แสดงโดย SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) บรรพบุรุษ: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) และ [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // ตั้งค่า "Browsed at a kiosk (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // ตั้งค่า "Browsed by individual (window)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // ตั้งค่า "Presented by a speaker (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

วนซ้ำสไลด์โชว์

**ผลลัพธ์:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

วนซ้ำสไลด์โชว์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

แสดงคำบรรยายในการแสดงสไลด์

**ผลลัพธ์:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

แสดงคำบรรยายในการแสดงสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

แสดงแอนิเมชันในการแสดงสไลด์

**ผลลัพธ์:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

แสดงแอนิเมชันในการแสดงสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

สีปากกาสำหรับการแสดงสไลด์

**ผลลัพธ์:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

ช่วงสไลด์

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

ช่วงสไลด์

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

ใช้จังหวะในการแสดงสไลด์

**ผลลัพธ์:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

ใช้จังหวะในการแสดงสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

แสดงการควบคุมสื่อ

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

แสดงการควบคุมสื่อ

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |