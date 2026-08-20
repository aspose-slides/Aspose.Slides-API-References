---
title: IMasterNotesSlide
second_title: Aspose.Slides for Java API 參考
description: 表示備註的主投影片。
type: docs
url: /zh-hant/com.aspose.slides/imasternotesslide/
---
**所有已實作的介面：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

代表備註的主投影片。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 回傳主備註投影片的 HeaderFooter 管理器。 |
| [getNotesStyle()](#getNotesStyle--) | 回傳備註文字的樣式。 |
| [getDrawingGuides()](#getDrawingGuides--) | 回傳主備註投影片的繪圖參考線集合。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

回傳主備註投影片的 HeaderFooter 管理器。唯讀 [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)。

**返回：**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

回傳備註文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回：**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

回傳主備註投影片的繪圖參考線集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // 在投影片中心以下加入新的水平繪圖參考線
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)