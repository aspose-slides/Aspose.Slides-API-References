---
title: NotesSlideManager
second_title: Référence API Aspose.Slides pour Java
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
>      // Supprimer les notes de la première diapositive
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Enregistrer la présentation sur le disque
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Renvoie la diapositive de notes pour la diapositive actuelle. |
| [addNotesSlide()](#addNotesSlide--) | Renvoie la diapositive de notes pour la diapositive actuelle, en créant une si elle n'existe pas. |
| [removeNotesSlide()](#removeNotesSlide--) | Supprime la diapositive de notes de la diapositive actuelle. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Renvoie la diapositive de notes pour la diapositive actuelle. Renvoie null si la diapositive n'a pas de diapositive de notes. Lecture seule [INotesSlide](../../com.aspose.slides/inotesslide).

**Renvoie:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Renvoie la diapositive de notes pour la diapositive actuelle, en créant une si elle n'existe pas.

**Renvoie:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) pour cette diapositive.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Supprime la diapositive de notes de la diapositive actuelle.