---
title: NotesSlideManager
second_title: Aspose.Slides for Java API hivatkozás
description: Jegyzetdia-kezelő.
type: docs
url: /hu/com.aspose.slides/notesslidemanager/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Jegyzetdia-kezelő.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Hozzáadja a jegyzeteket az első diához
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // A prezentáció mentése lemezre
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Az első dia jegyzeteinek eltávolítása
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // A prezentáció mentése lemezre
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Visszaadja az aktuális dia jegyzetdiát. |
| [addNotesSlide()](#addNotesSlide--) | Visszaadja az aktuális dia jegyzetdiát, ha az nincs, létrehozza. |
| [removeNotesSlide()](#removeNotesSlide--) | Eltávolítja az aktuális dia jegyzetdiát. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

Visszaadja az aktuális dia jegyzetdiát. Null értéket ad vissza, ha a dia nem rendelkezik jegyzetdiával. Csak olvasható [INotesSlide](../../com.aspose.slides/inotesslide).

**Visszatérési érték:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

Visszaadja az aktuális dia jegyzetdiát, ha az nincs, létrehozza.

**Visszatérési érték:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) ehhez a diához.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

Eltávolítja az aktuális dia jegyzetdiáját.