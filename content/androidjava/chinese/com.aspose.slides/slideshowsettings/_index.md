---
title: SlideShowSettings
second_title: Aspose.Slides for Android via Java API 参考
description: 表示演示文稿的幻灯片放映设置。
type: docs
url: /zh/com.aspose.slides/slideshowsettings/
---
**继承:**  
java.lang.Object  
```
public class SlideShowSettings
```

表示演示文稿的幻灯片放映设置。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Gets or sets the slide show type. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Gets or sets the slide show type. |
| [getLoop()](#getLoop--) | Loop Slide Show |
| [setLoop(boolean value)](#setLoop-boolean-) | Loop Slide Show |
| [getShowNarration()](#getShowNarration--) | Show Narration in Slide Show |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Show Narration in Slide Show |
| [getShowAnimation()](#getShowAnimation--) | Show Animation in Slide Show |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Show Animation in Slide Show |
| [getPenColor()](#getPenColor--) | Pen Color for Slide Show |
| [getSlides()](#getSlides--) | Slides range |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Slides range |
| [getUseTimings()](#getUseTimings--) | Use Timings in Slide Show |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Use Timings in Slide Show |
| [getShowMediaControls()](#getShowMediaControls--) | Show Media Controls |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Show Media Controls |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

获取或设置幻灯片放映类型。由以下 SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) 祖先：[BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // 设置 “Browsed at a kiosk (full screen)” 类型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // 设置 “Browsed by individual (window)” 类型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // 设置 “Presented by a speaker (full screen)” 类型
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**Returns:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Gets or sets the slide show type. Represented by the following  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // 设置 “Browsed at a kiosk (full screen)” 类型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // 设置 “Browsed by individual (window)” 类型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // 设置 “Presented by a speaker (full screen)” 类型
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Loop Slide Show

**Returns:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Loop Slide Show

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Show Narration in Slide Show

**Returns:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Show Narration in Slide Show

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Show Animation in Slide Show

**Returns:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Show Animation in Slide Show

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```
 


Pen Color for Slide Show

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Slides range

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

**Returns:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Slides range

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Use Timings in Slide Show

**Returns:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Use Timings in Slide Show

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Show Media Controls

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)


显示媒体控件

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |