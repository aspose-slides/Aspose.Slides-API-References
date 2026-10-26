---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: レイアウト スライドにプレースホルダーを追加できるマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

レイアウト スライドにプレースホルダーを追加できるマネージャーを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | 画像、テーブル、メディア、テキストなどのコンテンツを保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。 |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | 画像、テーブル、メディア、テキストなどのコンテンツを縦方向で保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。 |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | テキスト コンテンツを保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。 |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | テキスト コンテンツを縦方向で保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。 |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | 画像を保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。 |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | チャートを保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。 |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | テーブルを保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。 |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | SmartArt 図を保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。 |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | メディア オブジェクトを保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。 |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | オンライン画像を保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。 |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

画像、テーブル、メディア、テキストなどのコンテンツを保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。

--------------------

> ```
> 次の例は、レイアウト スライドに Content プレースホルダー シェイプを追加する方法を示しています。
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダー シェイプの X 座標です。 |
| y | float | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | float | 新しいプレースホルダー シェイプの幅です。 |
| height | float | 新しいプレースホルダー シェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) に Content プレースホルダーがあります。
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

画像、テーブル、メディア、テキストなどのコンテンツを縦方向で保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダー シェイプの X 座標です。 |
| y | float | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | float | 新しいプレースホルダー シェイプの幅です。 |
| height | float | 新しいプレースホルダー シェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) に Content (垂直) プレースホルダーがあります。
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

テキスト コンテンツを保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダー シェイプの X 座標です。 |
| y | float | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | float | 新しいプレースホルダー シェイプの幅です。 |
| height | float | 新しいプレースホルダー シェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) に Text プレースホルダーがあります。
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

テキスト コンテンツを縦方向で保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダー シェイプの X 座標です。 |
| y | float | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | float | 新しいプレースホルダー シェイプの幅です。 |
| height | float | 新しいプレースホルダー シェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) に Text (垂直) プレースホルダーがあります。
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

画像を保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダー シェイプの X 座標です。 |
| y | float | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | float | 新しいプレースホルダー シェイプの幅です。 |
| height | float | 新しいプレースホルダー シェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) に Picture プレースホルダーがあります。
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

チャートを保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。

--------------------

> ```
> 次の例は、レイアウト スライドに Chart プレースホルダー シェイプを追加する方法を示しています。
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダー シェイプの X 座標です。 |
| y | float | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | float | 新しいプレースホルダー シェイプの幅です。 |
| height | float | 新しいプレースホルダー シェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) に Chart プレースホルダーがあります。
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

テーブルを保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。

--------------------

> ```
> 次の例は、レイアウト スライドに Table プレースホルダー シェイプを追加する方法を示しています。
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダー シェイプの X 座標です。 |
| y | float | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | float | 新しいプレースホルダー シェイプの幅です。 |
| height | float | 新しいプレースホルダー シェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) に Table プレースホルダーがあります。
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

SmartArt 図を保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。

--------------------

> ```
> 次の例は、レイアウト スライドに SmartArt プレースホルダー シェイプを追加する方法を示しています。
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダー シェイプの X 座標です。 |
| y | float | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | float | 新しいプレースホルダー シェイプの幅です。 |
| height | float | 新しいプレースホルダー シェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) に SmartArt プレースホルダーがあります。
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

メディア オブジェクトを保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。

--------------------

> ```
> The following example shows how to add the Media placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダー シェイプの X 座標です。 |
| y | float | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | float | 新しいプレースホルダー シェイプの幅です。 |
| height | float | 新しいプレースホルダー シェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) に Media プレースホルダーがあります。
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

オンライン画像を保持するための新しいプレースホルダー シェイプをレイアウト スライドに追加します。

--------------------

> ```
> 次の例は、レイアウト スライドに Online Image プレースホルダー シェイプを追加する方法を示しています。
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダー シェイプの X 座標です。 |
| y | float | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | float | 新しいプレースホルダー シェイプの幅です。 |
| height | float | 新しいプレースホルダー シェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) に Online Image プレースホルダーがあります。