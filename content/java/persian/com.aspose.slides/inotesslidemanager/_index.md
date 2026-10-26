---
title: INotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: Notes slide manager.
type: docs
url: /fa/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

مدیر اسلاید یادداشت.
## متدها

| متد | توضیح |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند. |
| [addNotesSlide()](#addNotesSlide--) | اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند، در صورتی که وجود نداشته باشد یک اسلاید جدید ایجاد می‌کند. |
| [removeNotesSlide()](#removeNotesSlide--) | اسلاید یادداشت مربوط به اسلاید فعلی را حذف می‌کند. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند. اگر اسلاید یادداشت نداشته باشد، null برمی‌گرداند. فقط-خواندنی [INotesSlide](../../com.aspose.slides/inotesslide).

**بازمی‌گرداند:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند، در صورتی که وجود نداشته باشد یک اسلاید جدید ایجاد می‌کند.

**بازمی‌گرداند:**
- [INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) برای این اسلاید.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


اسلاید یادداشت مربوط به اسلاید فعلی را حذف می‌کند.