---
title: MasterHandoutSlide
second_title: Aspose.Slides for Java API リファレンス
description: ハンドアウト用のマスタースライドを表します。
type: docs
url: /ja/com.aspose.slides/masterhandoutslide/
---
**継承:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

ハンドアウト用のマスタースライドを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | マスターハンドアウトスライドの HeaderFooter マネージャーを返します。 |
| [getThemeManager()](#getThemeManager--) | テーママネージャーを返します。 |
| [getDrawingGuides()](#getDrawingGuides--) | マスターハンドアウトスライドの描画ガイドのコレクションを返します。 |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

マスタースライド上のシェイプをスライドに表示するかどうかを指定します。マスタースライド自体の場合、このプロパティは常に false を返します。読み書き可能な boolean。

**戻り値:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

マスタースライド上のシェイプをスライドに表示するかどうかを指定します。マスタースライド自体の場合、このプロパティは常に false を返します。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

マスターハンドアウトスライドの HeaderFooter マネージャーを返します。読み取り専用 [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)。

**戻り値:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

テーママネージャーを返します。読み取り専用 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)。

**戻り値:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

マスターハンドアウトスライドの描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // スライドの中心上に新しい水平描画ガイドを追加
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)