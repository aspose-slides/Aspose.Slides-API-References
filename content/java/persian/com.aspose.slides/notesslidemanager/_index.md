---
title: NotesSlideManager
second_title: مرجع API Aspose.Slides برای جاوا
description: مدیر اسلاید یادداشت.
type: docs
url: /fa/com.aspose.slides/notesslidemanager/
---
**وراثت:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

مدیر اسلاید یادداشت.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // یادداشت‌ها را به اولین اسلاید اضافه می‌کند
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // ارائه را بر روی دیسک ذخیره می‌کند
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // حذف یادداشت‌های اسلاید اول
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // ارائه را بر روی دیسک ذخیره می‌کند
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند. |
| [addNotesSlide()](#addNotesSlide--) | اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند و در صورت عدم وجود، یک اسلاید جدید ایجاد می‌کند. |
| [removeNotesSlide()](#removeNotesSlide--) | اسلاید یادداشت اسلاید فعلی را حذف می‌کند. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند. اگر اسلاید اسلاید یادداشت نداشته باشد، null باز می‌گرداند. فقط-خواندنی [INotesSlide](../../com.aspose.slides/inotesslide).

**بازگشت:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند و در صورت عدم وجود، یک اسلاید جدید ایجاد می‌کند.

**بازگشت:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) برای این اسلاید.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

اسلاید یادداشت اسلاید فعلی را حذف می‌کند.