---
title: SlideShowSettings
second_title: Aspose.Slides の Java API リファレンス
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
| [getSlideShowType()](#getSlideShowType--) | スライドショーのタイプを取得または設定します。 |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | スライドショーのタイプを取得または設定します。 |
| [getLoop()](#getLoop--) | スライドショーをループ |
| [setLoop(boolean value)](#setLoop-boolean-) | スライドショーをループ |
| [getShowNarration()](#getShowNarration--) | スライドショーでナレーションを表示 |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | スライドショーでナレーションを表示 |
| [getShowAnimation()](#getShowAnimation--) | スライドショーでアニメーションを表示 |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | スライドショーでアニメーションを表示 |
| [getPenColor()](#getPenColor--) | スライドショーのペンの色 |
| [getSlides()](#getSlides--) | スライド範囲 |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | スライド範囲 |
| [getUseTimings()](#getUseTimings--) | スライドショーでタイミングを使用 |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | スライドショーでタイミングを使用 |
| [getShowMediaControls()](#getShowMediaControls--) | メディアコントロールを表示 |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | メディアコントロールを表示 |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

スライドショーのタイプを取得または設定します。次の SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) によって表されます。祖先: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) と [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // "Browsed at a kiosk (full screen)" タイプを設定
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // "Browsed by individual (window)" タイプを設定
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // "Presented by a speaker (full screen)" タイプを設定
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

スライドショーのタイプを取得または設定します。次の SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) によって表されます。祖先: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) と [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // 「Browsed at a kiosk (full screen)」タイプを設定
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // 「Browsed by individual (window)」タイプを設定
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // 「Presented by a speaker (full screen)」タイプを設定
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

スライドショーをループ

**戻り値:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

スライドショーをループ

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

スライド範囲

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

スライド範囲

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