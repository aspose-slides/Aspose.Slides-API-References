---
title: NotesSlideManager
second_title: Aspose.Slides für Android über Java API-Referenz
description: Notizfolien-Manager.
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
>  // Instanziieren Sie ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Notizen zur ersten Folie hinzufügen
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Präsentation auf Festplatte speichern
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Instanziieren Sie ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Entfernen der Notizen der ersten Folie
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Präsentation auf Festplatte speichern
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Gibt die Notizfolie für die aktuelle Folie zurück. |
| [addNotesSlide()](#addNotesSlide--) | Gibt die Notizfolie für die aktuelle Folie zurück und erstellt sie, falls sie nicht existiert. |
| [removeNotesSlide()](#removeNotesSlide--) | Entfernt die Notizfolie der aktuellen Folie. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Gibt die Notizfolie für die aktuelle Folie zurück. Gibt null zurück, wenn die Folie keine Notizfolie hat. Nur lesbar [INotesSlide](../../com.aspose.slides/inotesslide).

**Rückgabewert:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Gibt die Notizfolie für die aktuelle Folie zurück und erstellt sie, falls sie nicht existiert.

**Rückgabewert:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) für diese Folie.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Entfernt die Notizfolie der aktuellen Folie.