---
title: LayoutSlide
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: レイアウト スライドを表します。
type: docs
url: /ja/com.aspose.slides/layoutslide/
---
**継承:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**すべての実装インターフェイス:**  
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)  
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

レイアウト スライドを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | レイアウト スライドの HeaderFooter マネージャーを返します。 |
| [getPlaceholderManager()](#getPlaceholderManager--) | レイアウト スライドのプレースホルダー マネージャーを返します。 |
| [getMasterSlide()](#getMasterSlide--) | レイアウトのマスタースライドを取得または設定します。 |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | レイアウトのマスタースライドを取得または設定します。 |
| [remove()](#remove--) | プレゼンテーションからレイアウトを削除します。 |
| [getThemeManager()](#getThemeManager--) | 上書きテーママネージャーを返します。 |
| [getLayoutType()](#getLayoutType--) | このレイアウト スライドのレイアウト タイプを返します。 |
| [getDependingSlides()](#getDependingSlides--) | このレイアウト スライドに依存するすべてのスライドの配列を返します。 |
| [hasDependingSlides()](#hasDependingSlides--) | このレイアウト スライドに依存するスライドが少なくとも1つ存在する場合に true を返します。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [getDrawingGuides()](#getDrawingGuides--) | レイアウト スライドの描画ガイドのコレクションを返します。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

レイアウト スライドの HeaderFooter マネージャーを返します。読み取り専用 [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)。

**戻り値:**  
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)

### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

レイアウト スライドのプレースホルダー マネージャーを返します。読み取り専用 [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)。

**戻り値:**  
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)

### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

レイアウトのマスタースライドを取得または設定します。読み書き可能 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**戻り値:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)

### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

レイアウトのマスタースライドを取得または設定します。読み書き可能 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```

プレゼンテーションからレイアウトを削除します。

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

上書きテーママネージャーを返します。読み取り専用 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**戻り値:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

このレイアウト スライドのレイアウト タイプを返します。読み取り専用 [SlideLayoutType](../../com.aspose.slides/slidelayouttype)。

**戻り値:**  
byte

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

このレイアウト スライドに依存するすべてのスライドの配列を返します。

**戻り値:**  
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

このレイアウト スライドに依存するスライドが少なくとも1つ存在する場合に true を返します。読み取り専用 boolean .

**戻り値:**  
boolean

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

マスタースライド上のシェイプをスライドに表示するかどうかを指定します。読み書き可能 boolean .

**戻り値:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

マスタースライド上のシェイプをスライドに表示するかどうかを指定します。読み書き可能 boolean .

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

レイアウト スライドの描画ガイドのコレクションを返します。読み取り専用 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // スライドの中心左側に新しい垂直描画ガイドを追加
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)