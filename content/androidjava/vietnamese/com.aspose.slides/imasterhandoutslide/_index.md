---
title: IMasterHandoutSlide
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho slide chính cho tài liệu phát tay.
type: docs
url: /vi/com.aspose.slides/imasterhandoutslide/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

Đại diện cho slide chính cho tài liệu phát tay.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide chính cho tài liệu phát tay. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về một tập hợp các hướng dẫn vẽ cho slide chính cho tài liệu phát tay. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Trả về trình quản lý HeaderFooter của slide chính cho tài liệu phát tay. Chỉ đọc [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Trả về:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Trả về một tập hợp các hướng dẫn vẽ cho slide chính cho tài liệu phát tay. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Thêm hướng dẫn vẽ ngang mới phía trên trung tâm slide
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)