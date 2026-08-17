---
title: IMasterNotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: Master notes slide manager.
type: docs
url: /ru/com.aspose.slides/imasternotesslidemanager/
---```
public interface IMasterNotesSlideManager
```

Менеджер слайда заметок мастера.
## Методы

| Method | Description |
| --- | --- |
| [getMasterNotesSlide()](#getMasterNotesSlide--) | Возвращает мастер для всех слайдов заметок этой презентации, если он существует, иначе возвращает null. |
| [setDefaultMasterNotesSlide()](#setDefaultMasterNotesSlide--) | Устанавливает мастер-слайд заметок по умолчанию для связанного слайда заметок. |
| [removeMasterNotesSlide()](#removeMasterNotesSlide--) | Удаляет мастер-слайд заметок. |
### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public abstract IMasterNotesSlide getMasterNotesSlide()
```


Возвращает мастер для всех слайдов заметок этой презентации, если он существует, иначе возвращает null. Только для чтения [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide).

**Возвращает:**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### setDefaultMasterNotesSlide() {#setDefaultMasterNotesSlide--}
```
public abstract IMasterNotesSlide setDefaultMasterNotesSlide()
```


Устанавливает мастер-слайд заметок по умолчанию для связанного слайда заметок.

**Возвращает:**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide) - По умолчанию мастер-слайд заметок [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### removeMasterNotesSlide() {#removeMasterNotesSlide--}
```
public abstract void removeMasterNotesSlide()
```


Удаляет мастер-слайд заметок.