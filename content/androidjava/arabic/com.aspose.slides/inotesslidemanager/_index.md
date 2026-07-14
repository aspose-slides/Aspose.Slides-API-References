---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: مدير شريحة الملاحظات.
type: docs
url: /ar/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

مدير شريحة الملاحظات.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | يعيد شريحة الملاحظات للشرائح الحالية. |
| [addNotesSlide()](#addNotesSlide--) | يعيد شريحة الملاحظات للشرائح الحالية، وينشئ واحدة إذا لم توجد. |
| [removeNotesSlide()](#removeNotesSlide--) | يزيل شريحة الملاحظات للشرائح الحالية. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

يعيد شريحة الملاحظات للشرائح الحالية. يعيد null إذا لم تحتوي الشريحة على شريحة ملاحظات. للقراءة فقط [INotesSlide](../../com.aspose.slides/inotesslide).

**الإرجاع:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

يعيد شريحة الملاحظات للشرائح الحالية، وينشئ واحدة إذا لم تكن موجودة.

**الإرجاع:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) لهذه الشريحة.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

يزيل شريحة الملاحظات للشرائح الحالية.