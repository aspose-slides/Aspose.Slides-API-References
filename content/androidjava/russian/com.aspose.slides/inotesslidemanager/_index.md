---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Менеджер слайдов заметок.
type: docs
url: /ru/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Менеджер слайдов заметок.
## Методы

| Метод | Описание |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Возвращает слайд заметок для текущего слайда. |
| [addNotesSlide()](#addNotesSlide--) | Возвращает слайд заметок для текущего слайда, создавая его, если он отсутствует. |
| [removeNotesSlide()](#removeNotesSlide--) | Удаляет слайд заметок текущего слайда. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Возвращает слайд заметок для текущего слайда. Возвращает null, если у слайда нет слайда заметок. **Только для чтения** [INotesSlide](../../com.aspose.slides/inotesslide).

**Возвращает:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Возвращает слайд заметок для текущего слайда, создавая его, если он отсутствует.

**Возвращает:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) для этого слайда.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Удаляет слайд заметок текущего слайда.