---
title: ILayoutSlide
second_title: Aspose.Slides for Android の Java API リファレンス
description: レイアウトスライドを表します。
type: docs
url: /ja/com.aspose.slides/ilayoutslide/
---
**実装されているすべてのインターフェース:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

レイアウトスライドを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | レイアウトスライドの HeaderFooter マネージャーを返します。 |
| [getPlaceholderManager()](#getPlaceholderManager--) | レイアウトスライドのプレースホルダー マネージャーを返します。 |
| [getMasterSlide()](#getMasterSlide--) | レイアウトのマスタースライドを取得または設定します。 |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | レイアウトのマスタースライドを取得または設定します。 |
| [getLayoutType()](#getLayoutType--) | このレイアウトスライドのレイアウトタイプを返します。 |
| [hasDependingSlides()](#hasDependingSlides--) | このレイアウトスライドに依存しているスライドが少なくとも1枚存在する場合に true を返します。 |
| [getDependingSlides()](#getDependingSlides--) | このレイアウトスライドに依存しているすべてのスライドの配列を返します。 |
| [remove()](#remove--) | プレゼンテーションからレイアウトを削除します。 |
| [getDrawingGuides()](#getDrawingGuides--) | レイアウトスライドの描画ガイドのコレクションを返します。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

レイアウトスライドの HeaderFooter マネージャーを返します。読み取り専用 [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)。

**戻り値:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

レイアウトスライドのプレースホルダー マネージャーを返します。読み取り専用 [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)。

**戻り値:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

レイアウトのマスタースライドを取得または設定します。読み取り/書き込み可能 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**戻り値:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

レイアウトのマスタースライドを取得または設定します。読み取り/書き込み可能 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

このレイアウトスライドのレイアウトタイプを返します。読み取り専用 [SlideLayoutType](../../com.aspose.slides/slidelayouttype)。

**戻り値:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

このレイアウトスライドに依存しているスライドが少なくとも1枚存在する場合に true を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

このレイアウトスライドに依存しているすべてのスライドの配列を返します。

**戻り値:**
com.aspose.slides.ISlide[] - このレイアウトスライドに依存しているすべてのスライドの配列
### remove() {#remove--}
```
public abstract void remove()
```

プレゼンテーションからレイアウトを削除します。

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

レイアウトスライドの描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // スライド中心の左側に新しい垂直描画ガイドを追加します
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)