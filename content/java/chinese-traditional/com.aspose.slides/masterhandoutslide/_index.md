---
title: MasterHandoutSlide
second_title: Aspose.Slides for Java API 參考
description: 表示 handout 的母投影片。
type: docs
url: /zh-hant/com.aspose.slides/masterhandoutslide/
---
**繼承:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**所有已實作的介面:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

表示 handout 的母投影片。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定在母投影片上的圖形是否應顯示在投影片上。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定在母投影片上的圖形是否應顯示在投影片上。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回 handout 的母投影片的 HeaderFooter 管理器。 |
| [getThemeManager()](#getThemeManager--) | 返回主題管理器。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回 handout 的母投影片的繪圖參考線集合。 |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定在母投影片上的圖形是否應顯示在投影片上。對於母投影片自身，此屬性永遠回傳 false。可讀寫 boolean。

**返回:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定在母投影片上的圖形是否應顯示在投影片上。對於母投影片自身，此屬性永遠回傳 false。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

返回 handout 的母投影片的 HeaderFooter 管理器。唯讀 [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)。

**返回:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

返回主題管理器。唯讀 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)。

**返回:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

返回 handout 的母投影片的繪圖參考線集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // 在投影片中心上方新增水平繪圖參考線
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)