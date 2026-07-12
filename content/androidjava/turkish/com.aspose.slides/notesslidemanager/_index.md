---
title: NotesSlideManager
second_title: Java API Referansı ile Android için Aspose.Slides
description: Not slayt yöneticisi.
type: docs
url: /tr/com.aspose.slides/notesslidemanager/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Not slayt yöneticisi.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
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
>  // Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // İlk slayttaki notları kaldırır
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Sunumu diske kaydeder
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Geçerli slayt için not slaytını döndürür. |
| [addNotesSlide()](#addNotesSlide--) | Geçerli slayt için not slaytını döndürür, yoksa bir tane oluşturur. |
| [removeNotesSlide()](#removeNotesSlide--) | Geçerli slaytın not slaydını kaldırır. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

Geçerli slayt için not slaytını döndürür. Slaytta not slaytı yoksa null döndürür. Yalnızca okuma [INotesSlide](../../com.aspose.slides/inotesslide).

**Döndürür:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

Geçerli slayt için not slaytını döndürür, yoksa bir tane oluşturur.

**Döndürür:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) bu slayt için.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

Geçerli slaytın not slaydını kaldırır.