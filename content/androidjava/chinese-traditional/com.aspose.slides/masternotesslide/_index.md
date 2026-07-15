---
title: MasterNotesSlide
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示備註的母投影片。
type: docs
url: /zh-hant/com.aspose.slides/masternotesslide/
---
**繼承：**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**全部已實作的介面：**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

代表備註的母投影片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定母投影片上的形狀是否應顯示於投影片上。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定母投影片上的形狀是否應顯示於投影片上。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回母備註投影片的 HeaderFooter 管理器。 |
| [getThemeManager()](#getThemeManager--) | 傳回主題管理器。 |
| [getNotesStyle()](#getNotesStyle--) | 傳回備註文字的樣式。 |
| [getDrawingGuides()](#getDrawingGuides--) | 傳回母備註投影片的繪圖參考線集合。 |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定母投影片上的形狀是否應顯示於投影片上。對於母投影片本身，此屬性始終傳回 false。可讀寫布林值。

**傳回：**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定母投影片上的形狀是否應顯示於投影片上。對於母投影片本身，此屬性始終傳回 false。可讀寫布林值。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

傳回母備註投影片的 HeaderFooter 管理器。唯讀 [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)。

**傳回：**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

傳回主題管理器。唯讀 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)。

**傳回：**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

傳回備註文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**傳回：**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

傳回母備註投影片的繪圖參考線集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // 在投影片中心下方新增水平繪圖參考線
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)