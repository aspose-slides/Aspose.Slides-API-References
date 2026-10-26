---
title: IMasterSlide
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーションのマスタースライドを表します。
type: docs
url: /ja/com.aspose.slides/imasterslide/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

プレゼンテーションのマスタースライドを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | マスタースライドの HeaderFooter マネージャーを返します。 |
| [getTitleStyle()](#getTitleStyle--) | タイトルテキストのスタイルを返します。 |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | 現在のマスタースライドを元に新しいマスタースライドを作成し、外部テーマを適用して、作成したマスタースライドをすべての依存スライドに適用します。 |
| [getBodyStyle()](#getBodyStyle--) | 本文テキストのスタイルを返します。 |
| [getOtherStyle()](#getOtherStyle--) | 他のテキストのスタイルを返します。 |
| [getLayoutSlides()](#getLayoutSlides--) | このマスタースライドの子レイアウトスライドのコレクションを返します。 |
| [getPreserve()](#getPreserve--) | 対応するマスターが、そのマスターに続くすべてのスライドが削除されたときに削除されるかどうかを判定します。 |
| [setPreserve(boolean value)](#setPreserve-boolean-) | 対応するマスターが、そのマスターに続くすべてのスライドが削除されたときに削除されるかどうかを判定します。 |
| [hasDependingSlides()](#hasDependingSlides--) | このマスタースライドに依存しているスライドが少なくとも1つ存在する場合に true を返します。 |
| [getDependingSlides()](#getDependingSlides--) | このマスタースライドに依存しているすべてのスライドの配列を返します。 |
| [getDrawingGuides()](#getDrawingGuides--) | マスタースライドの描画ガイドのコレクションを返します。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


マスタースライドの HeaderFooter マネージャーを返します。読み取り専用 [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)。

**戻り値:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```


タイトルテキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**戻り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


現在のマスタースライドを元に新しいマスタースライドを作成し、外部テーマを適用して、作成したマスタースライドをすべての依存スライドに適用します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | 外部テーマファイル (.thmx) のパス。 |

**戻り値:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 新しいテーマ適用 MasterSlide。
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```


本文テキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**戻り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```


他のテキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**戻り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```


このマスタースライドの子レイアウトスライドのコレクションを返します。読み取り専用 [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)。

--------------------

代替 API を使用してレイアウトスライドの追加/挿入/削除/クローン作成にアクセスするには、([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) プロパティを使用します。

**戻り値:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```


対応するマスターが、そのマスターに続くすべてのスライドが削除されたときに削除されるかどうかを判定します。注: Aspose.Slides は未使用のマスターを自動的に削除しません。未使用のマスターを実際に削除するには [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) を呼び出してください。読み書き可能 boolean。

**戻り値:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```


対応するマスターが、そのマスターに続くすべてのスライドが削除されたときに削除されるかどうかを判定します。注: Aspose.Slides は未使用のマスターを自動的に削除しません。未使用のマスターを実際に削除するには [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) を呼び出してください。読み書き可能 boolean。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


このマスタースライドに依存しているスライドが少なくとも1つ存在する場合に true を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


このマスタースライドに依存しているすべてのスライドの配列を返します。

**戻り値:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) の配列で、このマスタースライドに依存しています。
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


マスタースライドの描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // スライド中心の右側に新しい垂直描画ガイドを追加します
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)