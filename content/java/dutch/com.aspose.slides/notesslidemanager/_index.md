---
title: NotesSlideManager
second_title: Aspose.Slides voor Java API-referentie
description: Notitieslidebeheerder.
type: docs
url: /nl/com.aspose.slides/notesslidemanager/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Notitieslidebeheerder.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Maak een Presentation-object dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Voeg notities toe aan de eerste dia
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Sla de presentatie op naar schijf
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Maak een Presentation-object dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Verwijderen van notities van de eerste dia
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Sla de presentatie op naar schijf
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Retourneert de notitieslide voor de huidige slide. |
| [addNotesSlide()](#addNotesSlide--) | Retourneert de notitieslide voor de huidige slide, en maakt er één aan als die er niet is. |
| [removeNotesSlide()](#removeNotesSlide--) | Verwijdert de notitieslide van de huidige slide. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

Retourneert de notitieslide voor de huidige slide. Retourneert null als de slide geen notitieslide heeft. Alleen-lezen [INotesSlide](../../com.aspose.slides/inotesslide).

**Retourneert:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

Retourneert de notitieslide voor de huidige slide, en maakt er één aan als die er niet is.

**Retourneert:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) voor deze slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

Verwijdert de notitieslide van de huidige slide.