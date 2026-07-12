---
title: IMasterHandoutSlide
second_title: Aspose.Slides for Android の Java API リファレンス
description: 配布資料用のマスター スライドを表します。
type: docs
url: /ja/com.aspose.slides/imasterhandoutslide/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

配布資料用のマスター スライドを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 配布資料用マスター スライドの HeaderFooter マネージャーを返します。 |
| [getDrawingGuides()](#getDrawingGuides--) | 配布資料用マスター スライドの描画ガイドのコレクションを返します。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


配布資料用マスター スライドの HeaderFooter マネージャーを返します。読み取り専用 [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)。

**戻り値:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


配布資料用マスター スライドの描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // 新しい水平描画ガイドをスライド中央の上に追加
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)