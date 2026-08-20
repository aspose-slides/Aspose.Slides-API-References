---
title: LayoutSlide
second_title: Aspose.Slides for Java API 參考
description: 表示一個版面投影片。
type: docs
url: /zh-hant/com.aspose.slides/layoutslide/
---
**繼承:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**已實作的介面:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

表示一個版面投影片。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回此版面投影片的 HeaderFooter 管理員。 |
| [getPlaceholderManager()](#getPlaceholderManager--) | 傳回此版面投影片的 placeholder 管理員。 |
| [getMasterSlide()](#getMasterSlide--) | 傳回或設定此版面的 master slide。 |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | 傳回或設定此版面的 master slide。 |
| [remove()](#remove--) | 從簡報中移除版面。 |
| [getThemeManager()](#getThemeManager--) | 傳回覆寫的 theme manager。 |
| [getLayoutType()](#getLayoutType--) | 傳回此版面投影片的 layout 類型。 |
| [getDependingSlides()](#getDependingSlides--) | 傳回一個陣列，包含所有依賴此版面投影片的投影片。 |
| [hasDependingSlides()](#hasDependingSlides--) | 如果存在至少一個依賴此版面投影片的投影片，則傳回 true。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否在投影片上顯示 master slide 上的圖形。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否在投影片上顯示 master slide 上的圖形。 |
| [getDrawingGuides()](#getDrawingGuides--) | 傳回此版面投影片的 drawing guides 集合。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

傳回此版面投影片的 HeaderFooter 管理員。唯讀 [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)。

**返回：**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

傳回此版面投影片的 placeholder 管理員。唯讀 [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)。

**返回：**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

傳回或設定此版面的 master slide。可讀寫 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**返回：**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

傳回或設定此版面的 master slide。可讀寫 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```

從簡報中移除版面。
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

傳回覆寫的 theme manager。唯讀 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**返回：**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

傳回此版面投影片的 layout 類型。唯讀 [SlideLayoutType](../../com.aspose.slides/slidelayouttype)。

**返回：**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

傳回一個陣列，包含所有依賴此版面投影片的投影片。

**返回：**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

傳回 true，如果存在至少一個依賴此版面投影片的投影片。唯讀 boolean 。

**返回：**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定是否在投影片上顯示 master slide 上的圖形。可讀寫 boolean 。

**返回：**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定是否在投影片上顯示 master slide 上的圖形。可讀寫 boolean 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

傳回此版面投影片的 drawing guides 集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // 將新的垂直繪製參考線添加到投影片中心左側
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)