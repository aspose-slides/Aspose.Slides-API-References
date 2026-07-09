---
title: NotesSlideManager
second_title: Aspose.Slides pour Android via la référence API Java
description: Gestionnaire de diapositive de notes.
type: docs
url: /fr/com.aspose.slides/notesslidemanager/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Gestionnaire de diapositive de notes.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Instancier un objet Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Ajouter des notes à la première diapositive
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Enregistrer la présentation sur le disque
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Instancier un objet Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Suppression des notes de la première diapositive
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Enregistrer la présentation sur le disque
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Returns the notes slide for the current slide. |
| [addNotesSlide()](#addNotesSlide--) | Returns the notes slide for the current slide, creating one if there isn't. |
| [removeNotesSlide()](#removeNotesSlide--) | Removes notes slide of the current slide. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

Returns the notes slide for the current slide. Returns null if slide doesn't have notes slide. Read-only [INotesSlide](../../com.aspose.slides/inotesslide).

**Returns:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

Returns the notes slide for the current slide, creating one if there isn't.

**Returns:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) for this slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()

Supprime la diapositive de notes de la diapositive actuelle.
