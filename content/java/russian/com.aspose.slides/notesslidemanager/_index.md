---
title: NotesSlideManager
second_title: Справочник API Aspose.Slides для Java
description: Менеджер слайдов заметок.
type: docs
url: /ru/com.aspose.slides/notesslidemanager/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Менеджер слайдов заметок.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Создайте объект Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Добавьте заметки к первому слайду
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Сохраните презентацию на диск
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Создайте объект Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Удаление заметок первого слайда
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Сохраните презентацию на диск
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Возвращает слайд заметок для текущего слайда. |
| [addNotesSlide()](#addNotesSlide--) | Возвращает слайд заметок для текущего слайда, создавая его, если его нет. |
| [removeNotesSlide()](#removeNotesSlide--) | Удаляет слайд заметок текущего слайда. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Возвращает слайд заметок для текущего слайда. Возвращает null, если у слайда нет слайда заметок. Только для чтения [INotesSlide](../../com.aspose.slides/inotesslide).

**Возвращает:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Возвращает слайд заметок для текущего слайда, создавая его, если его нет.

**Возвращает:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) для этого слайда.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Удаляет слайд заметок текущего слайда.