---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API リファレンス
description: レイアウトスライドにプレースホルダーを追加できるマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

レイアウトスライドにプレースホルダーを追加できるマネージャーを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold content, such as a picture, table, media or text. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold content, such as a picture, table, media or text in a vertical direction. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold text content. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold text content in a vertical direction. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a picture. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a chart. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a table. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a SmartArt diagram. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a media object. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold an online image. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

画像、表、メディア、テキストなどのコンテンツを保持するためのプレースホルダー形状をレイアウトスライドに追加します。

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
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
| x | float | 新しいプレースホルダー形状の X 座標です。 |
| y | float | 新しいプレースホルダー形状の Y 座標です。 |
| width | float | 新しいプレースホルダー形状の幅です。 |
| height | float | 新しいプレースホルダー形状の高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) が Content プレースホルダーとして作成されました。
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

画像、表、メディア、テキストなどのコンテンツを縦方向で保持するためのプレースホルダー形状をレイアウトスライドに追加します。

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
| x | float | 新しいプレースホルダー形状の X 座標です。 |
| y | float | 新しいプレースホルダー形状の Y 座標です。 |
| width | float | 新しいプレースホルダー形状の幅です。 |
| height | float | 新しいプレースホルダー形状の高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) が Content (Vertical) プレースホルダーとして作成されました。
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

テキストコンテンツを保持するためのプレースホルダー形状をレイアウトスライドに追加します。

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
| x | float | 新しいプレースホルダー形状の X 座標です。 |
| y | float | 新しいプレースホルダー形状の Y 座標です。 |
| width | float | 新しいプレースホルダー形状の幅です。 |
| height | float | 新しいプレースホルダー形状の高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) が Text プレースホルダーとして作成されました。
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

テキストコンテンツを縦方向で保持するためのプレースホルダー形状をレイアウトスライドに追加します。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいプレースホルダー形状の X 座標です。 |
| y | float | 新しいプレースホルダー形状の Y 座標です。 |
| width | float | 新しいプレースホルダー形状の幅です。 |
| height | float | 新しいプレースホルダー形状の高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) が Text (Vertical) プレースホルダーとして作成されました。
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

画像を保持するためのプレースホルダー形状をレイアウトスライドに追加します。

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
| x | float | 新しいプレースホルダー形状の X 座標です。 |
| y | float | 新しいプレースホルダー形状の Y 座標です。 |
| width | float | 新しいプレースホルダー形状の幅です。 |
| height | float | 新しいプレースホルダー形状の高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) が Picture プレースホルダーとして作成されました。
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

チャートを保持するためのプレースホルダー形状をレイアウトスライドに追加します。

--------------------

> ```
> 次の例は、レイアウトスライドに Chart プレースホルダー形状を追加する方法を示しています。
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
| x | float | 新しいプレースホルダー形状の X 座標です。 |
| y | float | 新しいプレースホルダー形状の Y 座標です。 |
| width | float | 新しいプレースホルダー形状の幅です。 |
| height | float | 新しいプレースホルダー形状の高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) が Chart プレースホルダーとして作成されました。
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

表を保持するためのプレースホルダー形状をレイアウトスライドに追加します。

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
| x | float | 新しいプレースホルダー形状の X 座標です。 |
| y | float | 新しいプレースホルダー形状の Y 座標です。 |
| width | float | 新しいプレースホルダー形状の幅です。 |
| height | float | 新しいプレースホルダー形状の高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) が Table プレースホルダーとして作成されました。
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

SmartArt 図を保持するためのプレースホルダー形状をレイアウトスライドに追加します。

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
| x | float | 新しいプレースホルダー形状の X 座標です。 |
| y | float | 新しいプレースホルダー形状の Y 座標です。 |
| width | float | 新しいプレースホルダー形状の幅です。 |
| height | float | 新しいプレースホルダー形状の高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) が SmartArt プレースホルダーとして作成されました。
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

メディアオブジェクトを保持するためのプレースホルダー形状をレイアウトスライドに追加します。

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
| x | float | 新しいプレースホルダー形状の X 座標です。 |
| y | float | 新しいプレースホルダー形状の Y 座標です。 |
| width | float | 新しいプレースホルダー形状の幅です。 |
| height | float | 新しいプレースホルダー形状の高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) が Media プレースホルダーとして作成されました。
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

オンライン画像を保持するためのプレースホルダー形状をレイアウトスライドに追加します。

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
| x | float | 新しいプレースホルダー形状の X 座標です。 |
| y | float | 新しいプレースホルダー形状の Y 座標です。 |
| width | float | 新しいプレースホルダー形状の幅です。 |
| height | float | 新しいプレースホルダー形状の高さです。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) が Online Image プレースホルダーとして作成されました。