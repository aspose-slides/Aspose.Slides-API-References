---
title: NotesSlideManager
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Administrador de diapositivas de notas.
type: docs
url: /es/com.aspose.slides/notesslidemanager/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Administrador de diapositivas de notas.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Instanciar un objeto Presentation que representa un archivo de presentación
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Añadir notas a la primera diapositiva
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Guardar la presentación en disco
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Instanciar un objeto Presentation que representa un archivo de presentación
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Eliminar notas de la primera diapositiva
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Guardar la presentación en disco
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descripción |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Devuelve la diapositiva de notas para la diapositiva actual. |
| [addNotesSlide()](#addNotesSlide--) | Devuelve la diapositiva de notas para la diapositiva actual, creando una si no existe. |
| [removeNotesSlide()](#removeNotesSlide--) | Elimina la diapositiva de notas de la diapositiva actual. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Devuelve la diapositiva de notas para la diapositiva actual. Devuelve null si la diapositiva no tiene diapositiva de notas. Solo lectura [INotesSlide](../../com.aspose.slides/inotesslide).

**Devuelve:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Devuelve la diapositiva de notas para la diapositiva actual, creando una si no existe.

**Devuelve:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) para esta diapositiva.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Elimina la diapositiva de notas de la diapositiva actual.