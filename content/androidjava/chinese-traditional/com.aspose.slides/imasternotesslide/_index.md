---
title: IMasterNotesSlide
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示註解的母片投影片。
type: docs
url: /zh-hant/com.aspose.slides/imasternotesslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

表示註解的母片投影片。

## Methods

| 方法 | 說明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回母片註解投影片的 HeaderFooter 管理員。 |
| [getNotesStyle()](#getNotesStyle--) | 返回註解文字的樣式。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回母片註解投影片的繪圖參考線集合。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

返回母片註解投影片的 HeaderFooter 管理員。唯讀 [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)。

**返回：**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

返回註解文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回：**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

返回母片註解投影片的繪圖參考線集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // 在投影片中心下方加入新的水平繪圖參考線
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)