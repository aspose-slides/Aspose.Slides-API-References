---
title: NotesSlideManager
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Manajer slide catatan.
type: docs
url: /id/com.aspose.slides/notesslidemanager/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Manajer slide catatan.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Instansiasi objek Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Menambahkan catatan ke slide pertama
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Simpan presentasi ke disk
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Instansiasi objek Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Menghapus catatan dari slide pertama
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Simpan presentasi ke disk
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Metode | Deskripsi |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Mengembalikan slide catatan untuk slide saat ini. |
| [addNotesSlide()](#addNotesSlide--) | Mengembalikan slide catatan untuk slide saat ini, membuatnya jika tidak ada. |
| [removeNotesSlide()](#removeNotesSlide--) | Menghapus slide catatan dari slide saat ini. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Mengembalikan slide catatan untuk slide saat ini. Mengembalikan null jika slide tidak memiliki slide catatan. Hanya-baca [INotesSlide](../../com.aspose.slides/inotesslide).

**Mengembalikan:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Mengembalikan slide catatan untuk slide saat ini, membuatnya jika tidak ada.

**Mengembalikan:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) untuk slide ini.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Menghapus slide catatan dari slide saat ini.