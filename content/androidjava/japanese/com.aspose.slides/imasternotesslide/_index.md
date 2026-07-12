---
title: IMasterNotesSlide
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: ノート用のマスタースライドを表します。
type: docs
url: /ja/com.aspose.slides/imasternotesslide/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

ノート用のマスタースライドを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | マスターノートスライドの HeaderFooter マネージャーを返します。 |
| [getNotesStyle()](#getNotesStyle--) | ノートテキストのスタイルを返します。 |
| [getDrawingGuides()](#getDrawingGuides--) | マスターノートスライドの描画ガイドのコレクションを返します。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

マスターノートスライドの HeaderFooter マネージャーを返します。読み取り専用 [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**戻り値:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

ノートテキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle).

**戻り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

マスターノートスライドの描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // スライドの中心の下に新しい水平描画ガイドを追加
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)