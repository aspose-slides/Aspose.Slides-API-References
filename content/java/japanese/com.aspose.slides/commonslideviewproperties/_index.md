---
title: CommonSlideViewProperties
second_title: Aspose.Slides の Java API リファレンス
description: 共通スライドビュー プロパティを表します。
type: docs
url: /ja/com.aspose.slides/commonslideviewproperties/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

共通のスライドビュー プロパティを表します。

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // プレゼンテーションのビュー プロパティを設定しています
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // スライドビューのズーム値（パーセンテージ）
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // ノートビューのズーム値（パーセンテージ）
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getScale()](#getScale--) | ビューの拡大縮小率をパーセンテージで指定します。 |
| [setScale(int value)](#setScale-int-) | ビューの拡大縮小率をパーセンテージで指定します。 |
| [getVariableScale()](#getVariableScale--) | ビュー コンテンツが現在のウィンドウサイズに最適に合わせて自動的にスケールされるように指定します。 |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | ビュー コンテンツが現在のウィンドウサイズに最適に合わせて自動的にスケールされるように指定します。 |
| [getDrawingGuides()](#getDrawingGuides--) | 描画ガイドのコレクションを返します。 |
### getScale() {#getScale--}
```
public final int getScale()
```

ビューの拡大縮小率をパーセンテージで指定します。読み書き可能な int。

**戻り値:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

ビューの拡大縮小率をパーセンテージで指定します。読み書き可能な int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

ビュー コンテンツが現在のウィンドウサイズに最適に合わせて自動的にスケールされるように指定します。読み書き可能な boolean。

**戻り値:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

ビュー コンテンツが現在のウィンドウサイズに最適に合わせて自動的にスケールされるように指定します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // スライドの中心の右側に新しい垂直描画ガイドを追加
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // スライドの中心の下に新しい水平描画ガイドを追加
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)