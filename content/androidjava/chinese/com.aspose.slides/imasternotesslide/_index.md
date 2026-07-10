---
title: IMasterNotesSlide
second_title: Aspose.Slides for Android via Java API 参考
description: 表示备注的母版幻灯片。
type: docs
url: /zh/com.aspose.slides/imasternotesslide/
---
**所有实现的接口：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

表示备注的母版幻灯片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回主备注幻灯片的 HeaderFooter 管理器。 |
| [getNotesStyle()](#getNotesStyle--) | 返回备注文本的样式。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回主备注幻灯片的绘图参考线集合。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

返回主备注幻灯片的 HeaderFooter 管理器。只读 [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**返回：**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

返回备注文本的样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle).

**返回：**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

返回主备注幻灯片的绘图参考线集合。只读 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Adding the new horizontal drawing guide below the slide center
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)