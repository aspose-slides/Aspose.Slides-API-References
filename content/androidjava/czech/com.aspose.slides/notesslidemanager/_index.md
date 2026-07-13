---
title: NotesSlideManager
second_title: Aspose.Slides pro Android přes Java API Reference
description: Správce poznámkových snímků.
type: docs
url: /cs/com.aspose.slides/notesslidemanager/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Správce poznámkových snímků.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Přidejte poznámky k prvnímu snímku
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Uložte prezentaci na disk
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Odstraňování poznámek z prvního snímku
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Uložte prezentaci na disk
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Vrátí poznámkový snímek pro aktuální snímek. |
| [addNotesSlide()](#addNotesSlide--) | Vrátí poznámkový snímek pro aktuální snímek, vytvoří jej, pokud neexistuje. |
| [removeNotesSlide()](#removeNotesSlide--) | Odstraní poznámkový snímek aktuálního snímku. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

Vrátí poznámkový snímek pro aktuální snímek. Vrátí null, pokud snímek nemá poznámkový snímek. Pouze ke čtení [INotesSlide](../../com.aspose.slides/inotesslide).

**Vrací:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

Vrátí poznámkový snímek pro aktuální snímek, vytvoří jej, pokud neexistuje.

**Vrací:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) pro tento snímek.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

Odstraní poznámkový snímek aktuálního snímku.