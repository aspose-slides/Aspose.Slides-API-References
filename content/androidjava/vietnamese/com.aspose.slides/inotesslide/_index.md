---
title: INotesSlide
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một slide ghi chú trong bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/inotesslide/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Biểu diễn một slide ghi chú trong bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide ghi chú. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Trả về một TextFrame chứa văn bản ghi chú nếu có. |
| [getParentSlide()](#getParentSlide--) | Trả về một ParentSlide chỉ đọc [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Trả về trình quản lý HeaderFooter của slide ghi chú. Chỉ đọc [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Trả về:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Trả về một TextFrame chứa văn bản ghi chú nếu có. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Trả về một ParentSlide chỉ đọc [ISlide](../../com.aspose.slides/islide).

**Trả về:**
[ISlide](../../com.aspose.slides/islide)