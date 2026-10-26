---
title: SlideShowSettings
second_title: Aspose.Slides for Java API 参考
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
| [getSlideShowType()](#getSlideShowType--) | 获取或设置幻灯片放映类型。 |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | 获取或设置幻灯片放映类型。 |
| [getLoop()](#getLoop--) | 循环幻灯片放映 |
| [setLoop(boolean value)](#setLoop-boolean-) | 循环幻灯片放映 |
| [getShowNarration()](#getShowNarration--) | 在幻灯片放映中显示旁白 |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | 在幻灯片放映中显示旁白 |
| [getShowAnimation()](#getShowAnimation--) | 在幻灯片放映中显示动画 |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | 在幻灯片放映中显示动画 |
| [getPenColor()](#getPenColor--) | 幻灯片放映的笔颜色 |
| [getSlides()](#getSlides--) | 幻灯片范围 |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | 幻灯片范围 |
| [getUseTimings()](#getUseTimings--) | 在幻灯片放映中使用计时 |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | 在幻灯片放映中使用计时 |
| [getShowMediaControls()](#getShowMediaControls--) | 显示媒体控制 |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | 显示媒体控制 |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```


获取或设置幻灯片放映类型。由以下 SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) 祖先: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) 和 [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // 设置 "Browsed at a kiosk (full screen)" 类型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // 设置 "Browsed by individual (window)" 类型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // 设置 "Presented by a speaker (full screen)" 类型
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```


获取或设置幻灯片放映类型。由以下 SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) 祖先: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) 和 [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // 设置 "Browsed at a kiosk (full screen)" 类型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // 设置 "Browsed by individual (window)" 类型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // 设置 "Presented by a speaker (full screen)" 类型
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```


循环幻灯片放映

**返回值:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```


循环幻灯片放映

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```


在幻灯片放映中显示旁白

**返回值:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```


在幻灯片放映中显示旁白

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```


在幻灯片放映中显示动画

**返回值:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```


在幻灯片放映中显示动画

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```


幻灯片放映的笔颜色

**返回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```


幻灯片范围

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

**返回值:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```


幻灯片范围

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```


在幻灯片放映中使用计时

**返回值:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```


在幻灯片放映中使用计时

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```


显示媒体控制

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```


显示媒体控制

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |