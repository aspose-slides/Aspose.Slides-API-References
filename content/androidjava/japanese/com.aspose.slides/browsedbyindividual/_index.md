---
title: BrowsedByIndividual
second_title: Android 向け Aspose.Slides Java API リファレンス
description: 個別閲覧ウィンドウ
type: docs
url: /ja/com.aspose.slides/browsedbyindividual/
---
**継承:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

個別閲覧（ウィンドウ）

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | BrowsedByIndividual クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | ウィンドウにスクロールバーを表示 |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | ウィンドウにスクロールバーを表示 |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

BrowsedByIndividual クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```

ウィンドウにスクロールバーを表示

**戻り値:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

ウィンドウにスクロールバーを表示

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |