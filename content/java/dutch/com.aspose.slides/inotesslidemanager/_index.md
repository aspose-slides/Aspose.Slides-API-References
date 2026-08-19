---
title: INotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: Notitieslide manager.
type: docs
url: /nl/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Notitieslide manager.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Retourneert de notes slide voor de huidige slide. |
| [addNotesSlide()](#addNotesSlide--) | Retourneert de notes slide voor de huidige slide, en maakt er één aan indien er geen bestaat. |
| [removeNotesSlide()](#removeNotesSlide--) | Verwijdert de notes slide van de huidige slide. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


Retourneert de notes slide voor de huidige slide. Retourneert null als slide geen notes slide heeft. Alleen-lezen [INotesSlide](../../com.aspose.slides/inotesslide).

**Retourneert:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


Retourneert de notes slide voor de huidige slide, en maakt er één aan indien er geen bestaat.

**Retourneert:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) voor deze slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


Verwijdert de notes slide van de huidige slide.