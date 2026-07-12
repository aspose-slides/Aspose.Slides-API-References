---
title: NotesSlideManager
second_title: Aspose.Slides for Android Java API referenciája
description: Megjegyzésdia-kezelő.
type: docs
url: /hu/com.aspose.slides/notesslidemanager/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Az összes megvalósított interfész:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Megjegyzés dia kezelő.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Megjegyzéseket ad az első diára
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // A prezentációt lemezre menti
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
>      // Az első dia megjegyzéseit eltávolítja
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // A prezentációt lemezre menti
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Visszaadja a megjegyzésdiát a jelenlegi dián. |
| [addNotesSlide()](#addNotesSlide--) | Visszaadja a megjegyzésdiát a jelenlegi dián, és létrehozza, ha nincs. |
| [removeNotesSlide()](#removeNotesSlide--) | Eltávolítja a jelenlegi dia megjegyzésdiáját. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Visszaadja a megjegyzésdiát a jelenlegi dián. Null értéket ad vissza, ha a diához nincs megjegyzésdia. Csak olvasható [INotesSlide](../../com.aspose.slides/inotesslide).

**Visszatér:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Visszaadja a megjegyzésdiát a jelenlegi dián, és létrehozza, ha nincs.

**Visszatér:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) ehhez a diához.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Eltávolítja a jelenlegi dia megjegyzésdiáját.