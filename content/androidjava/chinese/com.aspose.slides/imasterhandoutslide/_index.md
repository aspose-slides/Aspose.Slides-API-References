---
title: IMasterHandoutSlide
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示讲义的母版幻灯片。
type: docs
url: /zh/com.aspose.slides/imasterhandoutslide/
---
**所有实现的接口：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

表示讲义的母版幻灯片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回主讲义幻灯片的 HeaderFooter 管理器。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回主讲义幻灯片的绘图参考线集合。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


返回主讲义幻灯片的 HeaderFooter 管理器。只读 [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)。

**返回：**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


返回主讲义幻灯片的绘图参考线集合。只读 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Adding the new horizontal drawing guide above the slide center
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)