---
title: NotesSlideManager
second_title: Aspose.Slides für Java API-Referenz
description: Manager für Notizfolien.
type: docs
url: /de/com.aspose.slides/notesslidemanager/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Notizfolien-Manager.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Instanziiert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Fügt Notizen zur ersten Folie hinzu
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Speichert die Präsentation auf dem Datenträger
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Instanziiert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Entfernt Notizen der ersten Folie
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Speichert die Präsentation auf dem Datenträger
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Gibt die notes slide für die aktuelle Folie zurück. |
| [addNotesSlide()](#addNotesSlide--) | Gibt die notes slide für die aktuelle Folie zurück, wobei sie erstellt wird, falls keine vorhanden ist. |
| [removeNotesSlide()](#removeNotesSlide--) | Entfernt notes slide der aktuellen Folie. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Gibt die notes slide für die aktuelle Folie zurück. Gibt null zurück, wenn die Folie keine notes slide hat. Nur lesbar [INotesSlide](../../com.aspose.slides/inotesslide).

**Rückgabe:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Gibt die notes slide für die aktuelle Folie zurück, wobei sie erstellt wird, falls keine vorhanden ist.

**Rückgabe:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) für diese Folie.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Entfernt notes slide der aktuellen Folie.