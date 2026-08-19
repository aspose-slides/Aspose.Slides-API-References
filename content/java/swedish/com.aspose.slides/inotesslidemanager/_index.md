---
title: INotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: Notbildshanterare.
type: docs
url: /sv/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Notbildshanterare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Returnerar notbilden för den aktuella bilden. |
| [addNotesSlide()](#addNotesSlide--) | Returnerar notbilden för den aktuella bilden och skapar en om den saknas. |
| [removeNotesSlide()](#removeNotesSlide--) | Tar bort notbilden för den aktuella bilden. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Returnerar notbilden för den aktuella bilden. Returnerar null om bilden inte har en notbild. Skrivskyddad [INotesSlide](../../com.aspose.slides/inotesslide).

**Returnerar:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Returnerar notbilden för den aktuella bilden och skapar en om den saknas.

**Returnerar:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) för denna bild.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Tar bort notbilden för den aktuella bilden.