---
title: INotesSlide
second_title: مرجع API Aspose.Slides برای جاوا
description: یک اسلاید یادداشت را در یک ارائه نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/inotesslide/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

یک اسلاید یادداشت را در یک ارائه نشان می‌دهد.

## روش‌ها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | HeaderFooter manager اسلاید یادداشت را باز می‌گرداند. |
| [getNotesTextFrame()](#getNotesTextFrame--) | TextFrame با متن یادداشت‌ها را باز می‌گرداند اگر وجود داشته باشد. |
| [getParentSlide()](#getParentSlide--) | ParentSlide فقط-خواندنی [ISlide](../../com.aspose.slides/islide) را باز می‌گرداند. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

HeaderFooter manager اسلاید یادداشت را باز می‌گرداند. فقط-خواندنی [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**باز می‌گرداند:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)

### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

TextFrame با متن یادداشت‌ها را باز می‌گرداند اگر وجود داشته باشد. فقط-خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**باز می‌گرداند:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

ParentSlide فقط-خواندنی [ISlide](../../com.aspose.slides/islide) را باز می‌گرداند.

**باز می‌گرداند:**
[ISlide](../../com.aspose.slides/islide)