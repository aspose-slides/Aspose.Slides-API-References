---
title: NotesSlideManager
second_title: Aspose.Slides untuk Referensi API Java
description: Manajer slide catatan.
type: docs
url: /id/com.aspose.slides/notesslidemanager/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Manajer slide catatan.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Add notes to first slide
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Save presentation to disk
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Removing notes of first slide
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Save presentation to disk
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Mengembalikan slide catatan untuk slide saat ini. |
| [addNotesSlide()](#addNotesSlide--) | Mengembalikan slide catatan untuk slide saat ini, membuat satu jika tidak ada. |
| [removeNotesSlide()](#removeNotesSlide--) | Menghapus slide catatan dari slide saat ini. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Mengembalikan slide catatan untuk slide saat ini. Mengembalikan null jika slide tidak memiliki slide catatan. Baca-saja [INotesSlide](../../com.aspose.slides/inotesslide).

**Mengembalikan:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Mengembalikan slide catatan untuk slide saat ini, membuat satu jika tidak ada.

**Mengembalikan:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) for this slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Menghapus slide catatan dari slide saat ini.