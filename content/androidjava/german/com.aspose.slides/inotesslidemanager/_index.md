---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Notizfolien-Manager.
type: docs
url: /de/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Notizfolien-Manager.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Gibt die Notizfolie für die aktuelle Folie zurück. |
| [addNotesSlide()](#addNotesSlide--) | Gibt die Notizfolie für die aktuelle Folie zurück und erstellt eine, falls keine vorhanden ist. |
| [removeNotesSlide()](#removeNotesSlide--) | Entfernt die Notizfolie der aktuellen Folie. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


Gibt die Notizfolie für die aktuelle Folie zurück. Gibt null zurück, wenn die Folie keine Notizfolie hat. Nur lesbar [INotesSlide](../../com.aspose.slides/inotesslide).

**Rückgabe:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


Gibt die Notizfolie für die aktuelle Folie zurück und erstellt eine, falls keine vorhanden ist.

**Rückgabe:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) für diese Folie.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


Entfernt die Notizfolie der aktuellen Folie.