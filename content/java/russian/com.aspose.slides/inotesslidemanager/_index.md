---
title: INotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: Менеджер слайдов с заметками.
type: docs
url: /ru/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Менеджер слайдов с заметками.
## Методы

| Метод | Описание |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Возвращает слайд с заметками для текущего слайда. |
| [addNotesSlide()](#addNotesSlide--) | Возвращает слайд с заметками для текущего слайда, создавая его, если он отсутствует. |
| [removeNotesSlide()](#removeNotesSlide--) | Удаляет слайд с заметками текущего слайда. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Возвращает слайд с заметками для текущего слайда. Возвращает null, если у слайда нет слайда с заметками. Только для чтения [INotesSlide](../../com.aspose.slides/inotesslide).

**Возвращаемое значение:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Возвращает слайд с заметками для текущего слайда, создавая его, если он отсутствует.

**Возвращаемое значение:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) для этого слайда.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Удаляет слайд с заметками текущего слайда.