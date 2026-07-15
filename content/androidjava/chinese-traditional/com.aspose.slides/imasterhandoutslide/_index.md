---
title: IMasterHandoutSlide
second_title: Aspose.Slides for Android 的 Java API 參考
description: 代表列印講義的母版投影片。
type: docs
url: /zh-hant/com.aspose.slides/imasterhandoutslide/
---
**所有實作的介面：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

代表列印講義的母版投影片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回主講義母版投影片的 HeaderFooter 管理器。 |
| [getDrawingGuides()](#getDrawingGuides--) | 傳回主講義母版投影片的繪圖指南集合。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


傳回 HeaderFooter 管理器的主講義母版投影片。唯讀 [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)。

**傳回：**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


傳回主講義母版投影片的繪圖指南集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // 在投影片中心上方新增水平繪圖指引
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)