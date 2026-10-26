---
title: NotesSlideManager
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: مدير شريحة الملاحظات.
type: docs
url: /ar/com.aspose.slides/notesslidemanager/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Notes slide manager.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // إنشاء كائن Presentation يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // إضافة ملاحظات إلى الشريحة الأولى
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // حفظ العرض التقديمي إلى القرص
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // إنشاء كائن Presentation يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // إزالة ملاحظات الشريحة الأولى
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // حفظ العرض التقديمي إلى القرص
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## الطرق

| Method | Description |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | إرجاع شريحة الملاحظات للشريحة الحالية. |
| [addNotesSlide()](#addNotesSlide--) | إرجاع شريحة الملاحظات للشريحة الحالية، وإنشاء واحدة إذا لم تتوفر. |
| [removeNotesSlide()](#removeNotesSlide--) | إزالة شريحة الملاحظات للشريحة الحالية. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


إرجاع شريحة الملاحظات للشريحة الحالية. إرجاع null إذا لم تحتوي الشريحة على شريحة ملاحظات. للقراءة فقط [INotesSlide](../../com.aspose.slides/inotesslide).

**القيمة المرجعة:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


إرجاع شريحة الملاحظات للشريحة الحالية، وإنشاء واحدة إذا لم تتوفر.

**القيمة المرجعة:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) لهذه الشريحة.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


إزالة شريحة الملاحظات للشريحة الحالية.