---
title: LayoutSlide
second_title: Aspose.Slides for Android via Java API 參考
description: 代表一個版面投影片。
type: docs
url: /zh-hant/com.aspose.slides/layoutslide/
---
**繼承:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**所有已實作的介面:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

代表一個版面投影片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回此版面投影片的 HeaderFooter 管理器。 |
| [getPlaceholderManager()](#getPlaceholderManager--) | 返回此版面投影片的佔位符管理器。 |
| [getMasterSlide()](#getMasterSlide--) | 返回或設定版面的母片投影片。 |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | 返回或設定版面的母片投影片。 |
| [remove()](#remove--) | 從簡報中移除版面。 |
| [getThemeManager()](#getThemeManager--) | 返回覆寫的主題管理器。 |
| [getLayoutType()](#getLayoutType--) | 返回此版面投影片的版面類型。 |
| [getDependingSlides()](#getDependingSlides--) | 返回一個陣列，包含所有依賴此版面投影片的投影片。 |
| [hasDependingSlides()](#hasDependingSlides--) | 如果存在至少一個依賴此版面投影片的投影片，則返回 true。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否在投影片上顯示母片上的圖形。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否在投影片上顯示母片上的圖形。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回此版面投影片的繪圖參考線集合。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

返回此版面投影片的 HeaderFooter 管理器。唯讀 [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**返回:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

返回此版面投影片的佔位符管理器。唯讀 [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**返回:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

返回或設定版面的母片投影片。讀寫 [IMasterSlide](../../com.aspose.slides/imasterslide).

**返回:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

返回或設定版面的母片投影片。讀寫 [IMasterSlide](../../com.aspose.slides/imasterslide).

**參數:**
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

返回覆寫的主題管理器。唯讀 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**返回:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

返回此版面投影片的版面類型。唯讀 [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**返回:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

返回一個陣列，包含所有依賴此版面投影片的投影片。

**返回:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

如果存在至少一個依賴此版面投影片的投影片，則返回 true。唯讀  boolean .

**返回:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定是否在投影片上顯示母片上的圖形。讀寫  boolean .

**返回:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定是否在投影片上顯示母片上的圖形。讀寫  boolean .

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

返回此版面投影片的繪圖參考線集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // 在投影片中心左側新增垂直繪圖參考線
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)