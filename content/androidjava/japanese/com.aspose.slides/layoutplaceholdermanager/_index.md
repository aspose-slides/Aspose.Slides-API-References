---
title: LayoutPlaceholderManager
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: レイアウトスライドにプレースホルダーを追加できるマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/layoutplaceholdermanager/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

レイアウトスライドにプレースホルダーを追加できるマネージャーを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | 画像、表、メディア、テキストなどのコンテンツを保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。 |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | 画像、表、メディア、テキストなどのコンテンツを縦方向で保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。 |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | テキストコンテンツを保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。 |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | テキストコンテンツを縦方向で保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。 |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | 画像を保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。 |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | チャートを保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。 |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | テーブルを保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。 |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | SmartArt 図を保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。 |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | メディアオブジェクトを保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。 |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | オンライン画像を保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。 |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


画像、表、メディア、テキストなどのコンテンツを保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダーシェイプの X 座標です。 |
| y | float | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | float | 新しいプレースホルダーシェイプの幅です。 |
| height | float | 新しいプレースホルダーシェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) (Content プレースホルダー)

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


画像、表、メディア、テキストなどのコンテンツを縦方向で保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダーシェイプの X 座標です。 |
| y | float | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | float | 新しいプレースホルダーシェイプの幅です。 |
| height | float | 新しいプレースホルダーシェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) (Content (Vertical) プレースホルダー)

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


テキストコンテンツを保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダーシェイプの X 座標です。 |
| y | float | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | float | 新しいプレースホルダーシェイプの幅です。 |
| height | float | 新しいプレースホルダーシェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) (Text プレースホルダー)

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


テキストコンテンツを縦方向で保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダーシェイプの X 座標です。 |
| y | float | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | float | 新しいプレースホルダーシェイプの幅です。 |
| height | float | 新しいプレースホルダーシェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) (Text (Vertical) プレースホルダー)

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


画像を保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダーシェイプの X 座標です。 |
| y | float | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | float | 新しいプレースホルダーシェイプの幅です。 |
| height | float | 新しいプレースホルダーシェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) (Picture プレースホルダー)

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


チャートを保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダーシェイプの X 座標です。 |
| y | float | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | float | 新しいプレースホルダーシェイプの幅です。 |
| height | float | 新しいプレースホルダーシェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) (Chart プレースホルダー)

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


テーブルを保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダーシェイプの X 座標です。 |
| y | float | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | float | 新しいプレースホルダーシェイプの幅です。 |
| height | float | 新しいプレースホルダーシェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) (Table プレースホルダー)

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


SmartArt 図を保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダーシェイプの X 座標です。 |
| y | float | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | float | 新しいプレースホルダーシェイプの幅です。 |
| height | float | 新しいプレースホルダーシェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) (SmartArt プレースホルダー)

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


メディアオブジェクトを保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダーシェイプの X 座標です。 |
| y | float | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | float | 新しいプレースホルダーシェイプの幅です。 |
| height | float | 新しいプレースホルダーシェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) (Media プレースホルダー)

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


オンライン画像を保持するための新しいプレースホルダーシェイプをレイアウトスライドに追加します。

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダーシェイプの X 座標です。 |
| y | float | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | float | 新しいプレースホルダーシェイプの幅です。 |
| height | float | 新しいプレースホルダーシェイプの高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 作成された [IAutoShape](../../com.aspose.slides/iautoshape) (Online Image プレースホルダー)