---
title: NotesSlideManager
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Menedżer slajdów notatek.
type: docs
url: /pl/com.aspose.slides/notesslidemanager/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Menedżer slajdu notatek.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Utwórz obiekt Presentation, który reprezentuje plik prezentacji
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Dodaj notatki do pierwszego slajdu
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Zapisz prezentację na dysku
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Utwórz obiekt Presentation, który reprezentuje plik prezentacji
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Usuwanie notatek z pierwszego slajdu
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Zapisz prezentację na dysku
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metody

| Metoda | Opis |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Zwraca slajd notatek dla bieżącego slajdu. |
| [addNotesSlide()](#addNotesSlide--) | Zwraca slajd notatek dla bieżącego slajdu, tworząc go, jeśli nie istnieje. |
| [removeNotesSlide()](#removeNotesSlide--) | Usuwa slajd notatek bieżącego slajdu. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

Zwraca slajd notatek dla bieżącego slajdu. Zwraca null, jeśli slajd nie posiada slajdu notatek. Tylko do odczytu [INotesSlide](../../com.aspose.slides/inotesslide).

**Zwraca:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

Zwraca slajd notatek dla bieżącego slajdu, tworząc go, jeśli nie istnieje.

**Zwraca:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) for this slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

Usuwa slajd notatek bieżącego slajdu.