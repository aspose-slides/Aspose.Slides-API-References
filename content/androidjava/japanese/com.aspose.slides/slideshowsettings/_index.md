---
title: SlideShowSettings
second_title: Aspose.Slides for Android via Java API リファレンス
description: プレゼンテーションのスライドショー設定を表します。
type: docs
url: /ja/com.aspose.slides/slideshowsettings/
---
**継承:**  
java.lang.Object
```
public class SlideShowSettings
```

プレゼンテーションのスライドショー設定を表します。
## メソッド

| メソッド | 説明 |
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

スライドショーのタイプを取得または設定します。 Represented by the following  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // "Browsed at a kiosk (full screen)" タイプを設定する
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // "Browsed by individual (window)" タイプを設定する
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // "Presented by a speaker (full screen)" タイプを設定する
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**  
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

スライドショーのタイプを取得または設定します。 Represented by the following  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // "Browsed at a kiosk (full screen)" タイプを設定する
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // "Browsed by individual (window)" タイプを設定する
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // "Presented by a speaker (full screen)" タイプを設定する
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |
### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

スライドショーのループ

**戻り値:**  
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

スライドショーのループ

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

スライドショーでナレーションを表示

**戻り値:**  
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

スライドショーでナレーションを表示

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

スライドショーでアニメーションを表示

**戻り値:**  
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

スライドショーでアニメーションを表示

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

スライドショーのペンの色

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

スライドの範囲

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

**戻り値:**  
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

スライドの範囲

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |
### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

スライドショーでタイミングを使用

**戻り値:**  
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

スライドショーでタイミングを使用

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

メディアコントロールを表示

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**  
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

メディアコントロールを表示

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |