---
title: ICommonSlideViewProperties
second_title: Aspose.Slides の Java API リファレンス
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
| [getScale()](#getScale--) | ビューの拡大縮小率をパーセンテージで指定します。 |
| [setScale(int value)](#setScale-int-) | ビューの拡大縮小率をパーセンテージで指定します。 |
| [getVariableScale()](#getVariableScale--) | ビューのコンテンツが現在のウィンドウサイズに最適に合わせて自動的にスケーリングされるように指定します。 |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | ビューのコンテンツが現在のウィンドウサイズに最適に合わせて自動的にスケーリングされるように指定します。 |
| [getDrawingGuides()](#getDrawingGuides--) | 描画ガイドのコレクションを返します。 |
### getScale() {#getScale--}
```
public abstract int getScale()
```


ビューの拡大縮小率をパーセンテージで指定します。読み書き int.

**戻り値:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


ビューの拡大縮小率をパーセンテージで指定します。読み書き int.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```


ビューのコンテンツが現在のウィンドウサイズに最適に合わせて自動的にスケーリングされるように指定します。読み書き boolean。

**戻り値:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```


ビューのコンテンツが現在のウィンドウサイズに最適に合わせて自動的にスケーリングされるように指定します。読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


描画ガイドのコレクションを返します。読取専用 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Adding the new horizontal drawing guide below the slide center
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)