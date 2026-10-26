---
title: IMasterNotesSlide
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho slide chính cho ghi chú.
type: docs
url: /vi/com.aspose.slides/imasternotesslide/
---
**Tất cả giao diện được triển khai:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

Đại diện cho slide chính cho ghi chú.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide ghi chú chính. |
| [getNotesStyle()](#getNotesStyle--) | Trả về kiểu dáng của văn bản ghi chú. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về một tập hợp các hướng dẫn vẽ cho slide ghi chú chính. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


Trả về trình quản lý HeaderFooter của slide ghi chú chính. Chỉ đọc [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**Trả về:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```


Trả về kiểu dáng của văn bản ghi chú. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Trả về một tập hợp các hướng dẫn vẽ cho slide ghi chú chính. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Thêm hướng dẫn vẽ ngang mới dưới trung tâm slide
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)