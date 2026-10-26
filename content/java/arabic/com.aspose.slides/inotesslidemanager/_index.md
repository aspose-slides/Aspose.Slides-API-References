---
title: INotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: مدير شريحة الملاحظات.
type: docs
url: /ar/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

مدير شريحة الملاحظات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Returns the notes slide for the current slide. |
| [addNotesSlide()](#addNotesSlide--) | Returns the notes slide for the current slide, creating one if there isn't. |
| [removeNotesSlide()](#removeNotesSlide--) | Removes notes slide of the current slide. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

يرجع شريحة الملاحظات للشراءة الحالية. يُرجع null إذا لم تكن الشريحة تحتوي على شريحة ملاحظات. للقراءة فقط [INotesSlide](../../com.aspose.slides/inotesslide).

**الإرجاع:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

يرجع شريحة الملاحظات للشراءة الحالية، مع إنشاء واحدة إذا لم تكن موجودة.

**الإرجاع:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) لهذه الشريحة.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

يزيل شريحة الملاحظات للشريحة الحالية.