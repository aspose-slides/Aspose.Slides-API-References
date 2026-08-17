---
title: MasterNotesSlide
second_title: Aspose.Slides for Java API リファレンス
description: ノート用のマスタースライドを表します。
type: docs
url: /ja/com.aspose.slides/masternotesslide/
---
**継承:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

ノート用マスタースライドを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | マスターノートスライドの HeaderFooter マネージャーを返します。 |
| [getThemeManager()](#getThemeManager--) | テーマ マネージャーを返します。 |
| [getNotesStyle()](#getNotesStyle--) | ノートテキストのスタイルを返します。 |
| [getDrawingGuides()](#getDrawingGuides--) | マスターノートスライド用の描画ガイドのコレクションを返します。 |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

マスタースライド上のシェイプをスライドに表示するかどうかを指定します。マスタースライド自体ではこのプロパティは常に false を返します。読み書き可能な boolean.

**戻り値:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

マスタースライド上のシェイプをスライドに表示するかどうかを指定します。マスタースライド自体ではこのプロパティは常に false を返します。読み書き可能な boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

マスターノートスライドの HeaderFooter マネージャーを返します。読み取り専用 [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)。

**戻り値:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

テーマ マネージャーを返します。読み取り専用 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)。

**戻り値:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

ノートテキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**戻り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

マスターノートスライド用の描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // スライドの中心の下に新しい水平描画ガイドを追加します
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)