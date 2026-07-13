---
title: INotesSlideManager
second_title: Aspose.Slides för Android via Java API-referens
description: Hanterare för notsidor.
type: docs
url: /sv/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Hanterare för notsidor.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Returnerar notsidan för den aktuella bilden. |
| [addNotesSlide()](#addNotesSlide--) | Returnerar notsidan för den aktuella bilden och skapar en om den saknas. |
| [removeNotesSlide()](#removeNotesSlide--) | Tar bort notsidan för den aktuella bilden. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


Returnerar notsidan för den aktuella bilden. Returnerar null om bilden inte har en notsida. Skrivskyddad [INotesSlide](../../com.aspose.slides/inotesslide).

**Returnerar:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


Returnerar notsidan för den aktuella bilden och skapar en om den saknas.

**Returnerar:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) för denna bild.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


Tar bort notsidan för den aktuella bilden.