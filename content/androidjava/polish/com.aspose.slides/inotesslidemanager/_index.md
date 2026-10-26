---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Menedżer slajdów notatek.
type: docs
url: /pl/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Menedżer slajdów notatek.
## Metody

| Metoda | Opis |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Zwraca slajd notatek dla bieżącego slajdu. |
| [addNotesSlide()](#addNotesSlide--) | Zwraca slajd notatek dla bieżącego slajdu, tworząc go, jeśli go nie ma. |
| [removeNotesSlide()](#removeNotesSlide--) | Usuwa slajd notatek bieżącego slajdu. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


Zwraca slajd notatek dla bieżącego slajdu. Zwraca null, jeśli slajd nie ma slajdu notatek. Tylko do odczytu [INotesSlide](../../com.aspose.slides/inotesslide).

**Zwraca:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


Zwraca slajd notatek dla bieżącego slajdu, tworząc go, jeśli go nie ma.

**Zwraca:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) dla tego slajdu.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


Usuwa slajd notatek bieżącego slajdu.