---
title: IMasterSlide
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーション内のマスタースライドを表します。
type: docs
url: /ja/com.aspose.slides/imasterslide/
---
**すべての実装インターフェイス:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

プレゼンテーション内のマスタースライドを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | マスタースライドの HeaderFooter マネージャーを返します。 |
| [getTitleStyle()](#getTitleStyle--) | タイトルテキストのスタイルを返します。 |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | 現在のスライドを基に新しいマスタースライドを作成し、外部テーマを適用して、作成したマスタースライドをすべての依存スライドに適用します。 |
| [getBodyStyle()](#getBodyStyle--) | 本文テキストのスタイルを返します。 |
| [getOtherStyle()](#getOtherStyle--) | その他のテキストのスタイルを返します。 |
| [getLayoutSlides()](#getLayoutSlides--) | このマスタースライドに対する子レイアウトスライドのコレクションを返します。 |
| [getPreserve()](#getPreserve--) | そのマスターに続くすべてのスライドが削除されたときに、対応するマスターが削除されるかどうかを判定します。 |
| [setPreserve(boolean value)](#setPreserve-boolean-) | そのマスターに続くすべてのスライドが削除されたときに、対応するマスターが削除されるかどうかを判定します。 |
| [hasDependingSlides()](#hasDependingSlides--) | このマスタースライドに依存しているスライドが少なくとも1つ存在する場合に true を返します。 |
| [getDependingSlides()](#getDependingSlides--) | このマスタースライドに依存しているすべてのスライドの配列を返します。 |
| [getDrawingGuides()](#getDrawingGuides--) | マスタースライドの描画ガイドのコレクションを返します。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

マスタースライドの HeaderFooter マネージャーを返します。読み取り専用 [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)。

**返り値:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

タイトルテキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

現在のスライドを基に新しいマスタースライドを作成し、外部テーマを適用して、作成したマスタースライドをすべての依存スライドに適用します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fname | java.lang.String | 外部テーマファイル (.thmx) へのパス。 |

**返り値:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 新しいテーマが適用された MasterSlide。

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

本文テキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

その他のテキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

このマスタースライドに対する子レイアウトスライドのコレクションを返します。読み取り専用 [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)。

--------------------

レイアウトスライドの追加/挿入/削除/クローン作成の代替 API には ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) プロパティを使用してアクセスできます。

**返り値:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

そのマスターに続くすべてのスライドが削除されたときに、対応するマスターが削除されるかどうかを判定します。注: Aspose.Slides は未使用のマスターを自動的に削除することはありません。実際に未使用のマスターを削除するには [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) を呼び出してください。読み書き可能な boolean。

**返り値:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

そのマスターに続くすべてのスライドが削除されたときに、対応するマスターが削除されるかどうかを判定します。注: Aspose.Slides は未使用のマスターを自動的に削除することはありません。実際に未使用のマスターを削除するには [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) を呼び出してください。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

このマスタースライドに依存しているスライドが少なくとも1つ存在する場合に true を返します。読み取り専用 boolean。

**返り値:**
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

このマスタースライドに依存しているすべてのスライドの配列を返します。

**返り値:**
com.aspose.slides.ISlide[] - このマスタースライドに依存している [ISlide](../../com.aspose.slides/islide) の配列

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

マスタースライドの描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // スライドセンターの右側に新しい垂直描画ガイドを追加しています
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返り値:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)