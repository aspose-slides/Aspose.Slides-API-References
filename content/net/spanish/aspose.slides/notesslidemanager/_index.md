---
title: NotesSlideManager
second_title: Referencia de la API de Aspose.Slides para .NET
description: Gestor de diapositivas de notas.
type: docs
weight: 8890
url: /es/aspose.slides/notesslidemanager/
---

## Clase NotesSlideManager

Gestor de diapositivas de notas.

```csharp
public sealed class NotesSlideManager : DomObject<Slide>, INotesSlideManager
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [NotesSlide](../../aspose.slides/notesslidemanager/notesslide) { get; } | Devuelve la diapositiva de notas para la diapositiva actual. Devuelve null si la diapositiva no tiene diapositiva de notas. Solo lectura [`INotesSlide`](../inotesslide). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddNotesSlide](../../aspose.slides/notesslidemanager/addnotesslide)() | Devuelve la diapositiva de notas para la diapositiva actual, creando una si no existe. |
| [RemoveNotesSlide](../../aspose.slides/notesslidemanager/removenotesslide)() | Elimina la diapositiva de notas de la diapositiva actual. |

### Ejemplos

El siguiente ejemplo muestra cómo agregar notas a una diapositiva específica de una presentación de PowerPoint.

```csharp
[C#]
	// Instanciar un objeto Presentation que representa un archivo de presentación
	using(Presentation presentation = new Presentation(dataDir + "AccessSlides.pptx")) {
	  // Agregar notas a la primera diapositiva
	  INotesSlideManager mgr = presentation.Slides[0].NotesSlideManager;
	  INotesSlide noteSlide = mgr.AddNotesSlide();
	  noteSlide.NotesTextFrame.Text = "Tus Notas";
	  // Guardar la presentación en disco
	  presentation.Save(dataDir + "RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
	}
```

El siguiente ejemplo muestra cómo eliminar notas de una diapositiva específica de una presentación de PowerPoint.

```csharp
[C#]
	// Instanciar un objeto Presentation que representa un archivo de presentación
	using(Presentation presentation = new Presentation(dataDir + "AccessSlides.pptx")) {
	  // Eliminar notas de la primera diapositiva
	  INotesSlideManager mgr = presentation.Slides[0].NotesSlideManager;
	  mgr.RemoveNotesSlide();
	  // Guardar la presentación en disco
	  presentation.Save(dataDir + "RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
	}
```

### Ver También

* clase [DomObject&lt;TParent&gt;](../domobject-1)
* clase [Slide](../slide)
* interfaz [INotesSlideManager](../inotesslidemanager)
* namespace [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->