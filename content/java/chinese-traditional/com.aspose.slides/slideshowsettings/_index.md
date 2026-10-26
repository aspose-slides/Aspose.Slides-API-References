---
title: SlideShowSettings
second_title: Aspose.Slides 的 Java API 參考
description: 表示簡報的投影片放映設定。
type: docs
url: /zh-hant/com.aspose.slides/slideshowsettings/
---
**繼承：**
java.lang.Object
```
public class SlideShowSettings
```

表示簡報的投影片放映設定。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | 取得或設定投影片播放類型。 |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | 取得或設定投影片播放類型。 |
| [getLoop()](#getLoop--) | 循環投影片播放 |
| [setLoop(boolean value)](#setLoop-boolean-) | 循環投影片播放 |
| [getShowNarration()](#getShowNarration--) | 在投影片播放中顯示旁白 |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | 在投影片播放中顯示旁白 |
| [getShowAnimation()](#getShowAnimation--) | 在投影片播放中顯示動畫 |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | 在投影片播放中顯示動畫 |
| [getPenColor()](#getPenColor--) | 投影片播放的筆色 |
| [getSlides()](#getSlides--) | 投影片範圍 |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | 投影片範圍 |
| [getUseTimings()](#getUseTimings--) | 在投影片播放中使用計時 |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | 在投影片播放中使用計時 |
| [getShowMediaControls()](#getShowMediaControls--) | 顯示媒體控制項 |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | 顯示媒體控制項 |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

取得或設定投影片播放類型。由以下 SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) 祖先：[BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk)、[PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) 和 [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // 設定「Browsed at a kiosk (full screen)」類型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // 設定「Browsed by individual (window)」類型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // 設定「Presented by a speaker (full screen)」類型
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**回傳值：**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

取得或設定投影片播放類型。由以下 SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) 祖先：[BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk)、[PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) 和 [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // 設定 "Browsed at a kiosk (full screen)" 類型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // 設定 "Browsed by individual (window)" 類型
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // 設定 "Presented by a speaker (full screen)" 類型
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

循環投影片播放

**回傳值：**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

循環投影片播放

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

在投影片播放中顯示旁白

**回傳值：**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

在投影片播放中顯示旁白

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

在投影片播放中顯示動畫

**回傳值：**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

在投影片播放中顯示動畫

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

投影片播放的筆色

**回傳值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

投影片範圍

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

**回傳值：**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

投影片範圍

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

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

在投影片播放中使用計時

**回傳值：**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

在投影片播放中使用計時

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

顯示媒體控制項

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**回傳值：**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

顯示媒體控制項

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |