---
title: MasterSlide
second_title: Java APIリファレンスによる Android 用 Aspose.Slides
description: プレゼンテーション内のマスタースライドを表します。
type: docs
url: /ja/com.aspose.slides/masterslide/
---
**継承:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

プレゼンテーション内のマスタースライドを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | マスタースライドの HeaderFooter マネージャーを返します。 |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | 現在のスライドを基に新しいマスタースライドを作成し、外部テーマを適用して、作成されたマスタースライドをすべての依存スライドに適用します。 |
| [getTitleStyle()](#getTitleStyle--) | タイトルテキストのスタイルを返します。 |
| [getBodyStyle()](#getBodyStyle--) | 本文テキストのスタイルを返します。 |
| [getOtherStyle()](#getOtherStyle--) | その他のテキストのスタイルを返します。 |
| [getLayoutSlides()](#getLayoutSlides--) | このマスタースライドの子レイアウトスライドのコレクションを返します。 |
| [getPreserve()](#getPreserve--) | そのマスターに続くすべてのスライドが削除されたときに、対応するマスターが削除されるかどうかを決定します。 |
| [setPreserve(boolean value)](#setPreserve-boolean-) | そのマスターに続くすべてのスライドが削除されたときに、対応するマスターが削除されるかどうかを決定します。 |
| [getDependingSlides()](#getDependingSlides--) | このマスタースライドに依存するすべてのスライドの配列を返します。 |
| [hasDependingSlides()](#hasDependingSlides--) | このマスタースライドに依存するスライドが少なくとも1つ存在する場合に true を返します。 |
| [getThemeManager()](#getThemeManager--) | テーママネージャーを返します。 |
| [getName()](#getName--) | マスタースライドの名前を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | マスタースライドの名前を取得または設定します。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | マスタースライド上のシェイプをスライド上に表示するかどうかを指定します。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | マスタースライド上のシェイプをスライド上に表示するかどうかを指定します。 |
| [getDrawingGuides()](#getDrawingGuides--) | マスタースライドの描画ガイドのコレクションを返します。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

マスタースライドの HeaderFooter マネージャーを返します。読み取り専用 [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)。

**戻り値:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

現在のスライドを基に新しいマスタースライドを作成し、外部テーマを適用して、作成されたマスタースライドをすべての依存スライドに適用します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fname | java.lang.String | 外部テーマファイル (.thmx) のパス。 |

**戻り値:**
- 新しいテーマ適用マスタースライド。 [IMasterSlide](../../com.aspose.slides/imasterslide)
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

タイトルテキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**戻り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

本文テキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**戻り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

その他のテキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**戻り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

このマスタースライドの子レイアウトスライドのコレクションを返します。読み取り専用 [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)。

--------------------

レイアウトスライドの追加/挿入/削除/クローン作成の代替 API にアクセスするには、 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) プロパティを使用します。

**戻り値:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

そのマスターに続くすべてのスライドが削除されたときに、対応するマスターが削除されるかどうかを決定します。注: Aspose.Slides は未使用のマスターを自動的に削除しません。未使用のマスターを実際に削除するには [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) を呼び出します。読み書き可能 boolean 。

**戻り値:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

そのマスターに続くすべてのスライドが削除されたときに、対応するマスターが削除されるかどうかを決定します。注: Aspose.Slides は未使用のマスターを自動的に削除しません。未使用のマスターを実際に削除するには [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) を呼び出します。読み書き可能 boolean 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

このマスタースライドに依存するすべてのスライドの配列を返します。

**戻り値:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) の配列
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

このマスタースライドに依存するスライドが少なくとも1つ存在する場合に true を返します。読み取り専用 boolean 。

**戻り値:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

テーママネージャーを返します。読み取り専用 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)。

**戻り値:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

マスタースライドの名前を取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

マスタースライドの名前を取得または設定します。読み書き可能 String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

マスタースライド上のシェイプをスライド上に表示するかどうかを指定します。マスタースライド自体ではこのプロパティは常に false を返します。読み書き可能 boolean 。

**戻り値:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

マスタースライド上のシェイプをスライド上に表示するかどうかを指定します。マスタースライド自体ではこのプロパティは常に false を返します。読み書き可能 boolean 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
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