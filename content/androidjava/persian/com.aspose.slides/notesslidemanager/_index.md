---
title: NotesSlideManager
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مدیر اسلاید یادداشت‌ها.
type: docs
url: /fa/com.aspose.slides/notesslidemanager/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

مدیر اسلاید یادداشت‌ها.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // یادداشت‌ها را به اسلاید اول اضافه می‌کند
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // ارائه را در دیسک ذخیره می‌کند
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
>      // یادداشت‌های اسلاید اول را حذف می‌کند
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // ارائه را در دیسک ذخیره می‌کند
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند. |
| [addNotesSlide()](#addNotesSlide--) | اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند و در صورت عدم وجود، یکی ایجاد می‌کند. |
| [removeNotesSlide()](#removeNotesSlide--) | اسلاید یادداشت اسلاید فعلی را حذف می‌کند. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند. اگر اسلاید یادداشت نداشته باشد، مقدار null را برمی‌گرداند. فقط خواندنی [INotesSlide](../../com.aspose.slides/inotesslide).

**بازگشت:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

اسلاید یادداشت را برای اسلاید فعلی برمی‌گرداند و در صورت عدم وجود، یکی ایجاد می‌کند.

**بازگشت:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) برای این اسلاید.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

اسلاید یادداشت اسلاید فعلی را حذف می‌کند.