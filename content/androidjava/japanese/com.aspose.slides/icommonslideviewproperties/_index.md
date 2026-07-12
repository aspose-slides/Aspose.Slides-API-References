---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: 共通スライドビュー プロパティを表します。
type: docs
url: /ja/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

共通スライドビュー プロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getScale()](#getScale--) | Specifies the view scaling ratio in percentages. |
| [setScale(int value)](#setScale-int-) | Specifies the view scaling ratio in percentages. |
| [getVariableScale()](#getVariableScale--) | Specifies that the view content should automatically scale to best fit the current window size. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Specifies that the view content should automatically scale to best fit the current window size. |
| [getDrawingGuides()](#getDrawingGuides--) | Returns the collection of the drawing guides. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

ビューのスケーリング比率をパーセンテージで指定します。 読み取り/書き込み int。

**戻り値:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

ビューのスケーリング比率をパーセンテージで指定します。 読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

ビューのコンテンツが現在のウィンドウサイズに最適に合わせて自動的にスケールされるように指定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

ビューのコンテンツが現在のウィンドウサイズに最適に合わせて自動的にスケールされるように指定します。 読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

描画ガイドのコレクションを返します。 読み取り専用 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // スライド中心の右側に新しい垂直描画ガイドを追加します
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // スライド中心の下に新しい水平描画ガイドを追加します
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)