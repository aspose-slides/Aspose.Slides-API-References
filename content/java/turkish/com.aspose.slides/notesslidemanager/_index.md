---
title: NotesSlideManager
second_title: Aspose.Slides for Java API Referansı
description: Not slaytı yöneticisi.
type: docs
url: /tr/com.aspose.slides/notesslidemanager/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Not slaytı yöneticisi.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Sunum dosyasını temsil eden bir Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // İlk slayta not ekler
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Sunumu diske kaydeder
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Sunum dosyasını temsil eden bir Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // İlk slaydın notlarını kaldırır
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Sunumu diske kaydeder
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Mevcut slayt için not slaytını döndürür. |
| [addNotesSlide()](#addNotesSlide--) | Mevcut slayt için not slaytını döndürür, yoksa bir tane oluşturur. |
| [removeNotesSlide()](#removeNotesSlide--) | Mevcut slaytın not slaytını kaldırır. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

Mevcut slayt için not slaytını döndürür. Slaytta not slaytı yoksa null döndürür. Salt okunur [INotesSlide](../../com.aspose.slides/inotesslide).

**Döndürür:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

Mevcut slayt için not slaytını döndürür, yoksa bir tane oluşturur.

**Döndürür:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) bu slayt için.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

Mevcut slaytın not slaytını kaldırır.