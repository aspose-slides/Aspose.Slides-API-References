---
title: NotesSlideManager
second_title: Aspose.Slides för Java API-referens
description: Anteckningsbildshanterare.
type: docs
url: /sv/com.aspose.slides/notesslidemanager/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Anteckningsbildshanterare.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Skapa ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Lägg till anteckningar på den första bilden
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Spara presentationen till disk
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Skapa ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Tar bort anteckningar från den första bilden
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Spara presentationen till disk
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Returnerar anteckningsbilden för den aktuella bilden. |
| [addNotesSlide()](#addNotesSlide--) | Returnerar anteckningsbilden för den aktuella bilden och skapar en om den saknas. |
| [removeNotesSlide()](#removeNotesSlide--) | Tar bort anteckningsbilden för den aktuella bilden. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Returnerar anteckningsbilden för den aktuella bilden. Returnerar null om bilden inte har någon anteckningsbild. Skrivskyddad [INotesSlide](../../com.aspose.slides/inotesslide).

**Returnerar:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Returnerar anteckningsbilden för den aktuella bilden och skapar en om den saknas.

**Returnerar:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) för den här bilden.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Tar bort anteckningsbilden för den aktuella bilden.