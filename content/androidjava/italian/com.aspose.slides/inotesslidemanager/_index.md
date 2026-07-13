---
title: INotesSlideManager
second_title: Aspose.Slides per Android via Java API Reference
description: Gestore delle diapositive delle note.
type: docs
url: /it/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Gestore delle diapositive delle note.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Restituisce la diapositiva delle note per la diapositiva corrente. |
| [addNotesSlide()](#addNotesSlide--) | Restituisce la diapositiva delle note per la diapositiva corrente, creandone una se non esiste. |
| [removeNotesSlide()](#removeNotesSlide--) | Rimuove la diapositiva delle note della diapositiva corrente. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


Restituisce la diapositiva delle note per la diapositiva corrente. Restituisce null se la diapositiva non ha una diapositiva delle note. Solo lettura [INotesSlide](../../com.aspose.slides/inotesslide).

**Returns:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


Restituisce la diapositiva delle note per la diapositiva corrente, creandone una se non esiste.

**Returns:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) per questa diapositiva.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


Rimuove la diapositiva delle note della diapositiva corrente.