---
title: INotesSlide
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک اسلاید یادداشت در یک ارائه را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/inotesslide/
---
**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

یک اسلاید یادداشت در یک ارائه را نشان می‌دهد.
## متدها

| متد | توضیحات |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید یادداشت را بر می‌گرداند. |
| [getNotesTextFrame()](#getNotesTextFrame--) | اگر موجود باشد، یک TextFrame با متن یادداشت‌ها را بر می‌گرداند. |
| [getParentSlide()](#getParentSlide--) | یک ParentSlide فقط-خواندنی [ISlide](../../com.aspose.slides/islide) را بر می‌گرداند. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید یادداشت را بر می‌گرداند. فقط-خواندنی [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**بازگشت:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

اگر موجود باشد، یک TextFrame با متن یادداشت‌ها را بر می‌گرداند. فقط-خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

یک ParentSlide فقط-خواندنی [ISlide](../../com.aspose.slides/islide) را بر می‌گرداند.

**بازگشت:**
[ISlide](../../com.aspose.slides/islide)