---
title: NotesSlideManager
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Gestore delle diapositive note.
type: docs
url: /it/com.aspose.slides/notesslidemanager/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Gestore delle diapositive note.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Istanzia un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Aggiunge note alla prima diapositiva
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Salva la presentazione su disco
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Istanzia un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Rimuove le note della prima diapositiva
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Salva la presentazione su disco
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Restituisce la diapositiva note per la diapositiva corrente. |
| [addNotesSlide()](#addNotesSlide--) | Restituisce la diapositiva note per la diapositiva corrente, creandone una se non esiste. |
| [removeNotesSlide()](#removeNotesSlide--) | Rimuove la diapositiva note della diapositiva corrente. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Restituisce la diapositiva note per la diapositiva corrente. Restituisce null se la diapositiva non ha una diapositiva note. Solo lettura [INotesSlide](../../com.aspose.slides/inotesslide).

**Restituisce:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Restituisce la diapositiva note per la diapositiva corrente, creandone una se non esiste.

**Restituisce:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) per questa diapositiva.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Rimuove la diapositiva note della diapositiva corrente.