---
title: SlideShowSettings
second_title: Java API를 통한 Android용 Aspose.Slides 참조
description: 프레젠테이션의 슬라이드 쇼 설정을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/slideshowsettings/
---
**상속:**
java.lang.Object
```
public class SlideShowSettings
```

프레젠테이션의 슬라이드 쇼 설정을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | 슬라이드 쇼 유형을 가져오거나 설정합니다. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | 슬라이드 쇼 유형을 가져오거나 설정합니다. |
| [getLoop()](#getLoop--) | 슬라이드 쇼 루프 |
| [setLoop(boolean value)](#setLoop-boolean-) | 슬라이드 쇼 루프 |
| [getShowNarration()](#getShowNarration--) | 슬라이드 쇼에서 내레이션 표시 |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | 슬라이드 쇼에서 내레이션 표시 |
| [getShowAnimation()](#getShowAnimation--) | 슬라이드 쇼에서 애니메이션 표시 |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | 슬라이드 쇼에서 애니메이션 표시 |
| [getPenColor()](#getPenColor--) | 슬라이드 쇼용 펜 색상 |
| [getSlides()](#getSlides--) | 슬라이드 범위 |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | 슬라이드 범위 |
| [getUseTimings()](#getUseTimings--) | 슬라이드 쇼에서 타이밍 사용 |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | 슬라이드 쇼에서 타이밍 사용 |
| [getShowMediaControls()](#getShowMediaControls--) | 미디어 컨트롤 표시 |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | 미디어 컨트롤 표시 |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

슬라이드 쇼 유형을 가져오거나 설정합니다. 다음 SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) 조상: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) 및 [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // "Browsed at a kiosk (full screen)" 유형을 설정
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // "Browsed by individual (window)" 유형을 설정
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // "Presented by a speaker (full screen)" 유형을 설정
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

슬라이드 쇼 유형을 가져오거나 설정합니다. 다음 SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) 조상: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) 및 [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // "Browsed at a kiosk (full screen)" 유형을 설정
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // "Browsed by individual (window)" 유형을 설정
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // "Presented by a speaker (full screen)" 유형을 설정
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

슬라이드 쇼 루프

**반환값:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

슬라이드 쇼 루프

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

슬라이드 쇼에서 내레이션 표시

**반환값:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

슬라이드 쇼에서 내레이션 표시

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

슬라이드 쇼에서 애니메이션 표시

**반환값:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

슬라이드 쇼에서 애니메이션 표시

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

슬라이드 쇼용 펜 색상

**반환값:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

슬라이드 범위

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

**반환값:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

슬라이드 범위

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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

슬라이드 쇼에서 타이밍 사용

**반환값:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

슬라이드 쇼에서 타이밍 사용

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

미디어 컨트롤 표시

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

미디어 컨트롤 표시

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |