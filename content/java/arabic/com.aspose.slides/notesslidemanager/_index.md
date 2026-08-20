---
title: NotesSlideManager
second_title: مرجع API لـ Aspose.Slides للغة Java
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

مدير شريحة الملاحظات.

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
>      // حفظ العرض التقديمي على القرص
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
>      // حفظ العرض التقديمي على القرص
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | يرجع شريحة الملاحظات للشرائح الحالية. |
| [addNotesSlide()](#addNotesSlide--) | يرجع شريحة الملاحظات للشرائح الحالية، وينشئ واحدة إذا لم توجد. |
| [removeNotesSlide()](#removeNotesSlide--) | يزيل شريحة الملاحظات للشرائح الحالية. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


يرجع شريحة الملاحظات للشرائح الحالية. يرجع null إذا لم تحتوي الشريحة على شريحة ملاحظات. للقراءة فقط [INotesSlide](../../com.aspose.slides/inotesslide).

**القيمة المرجعة:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


يرجع شريحة الملاحظات للشرائح الحالية، وينشئ واحدة إذا لم توجد.

**القيمة المرجعة:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) لهذه الشريحة.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


يزيل شريحة الملاحظات للشرائح الحالية.