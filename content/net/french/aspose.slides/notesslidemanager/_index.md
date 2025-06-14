---
title: NotesSlideManager
second_title: Référence API Aspose.Slides pour .NET
description: Gestionnaire de diapositive de notes.
type: docs
weight: 8890
url: /fr/aspose.slides/notesslidemanager/
---

## Classe NotesSlideManager

Gestionnaire de diapositive de notes.

```csharp
public sealed class NotesSlideManager : DomObject<Slide>, INotesSlideManager
```

## Propriétés

| Nom | Description |
| --- | --- |
| [NotesSlide](../../aspose.slides/notesslidemanager/notesslide) { get; } | Retourne la diapositive de notes pour la diapositive actuelle. Retourne null si la diapositive n'a pas de diapositive de notes. Lecture seule [`INotesSlide`](../inotesslide). |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddNotesSlide](../../aspose.slides/notesslidemanager/addnotesslide)() | Retourne la diapositive de notes pour la diapositive actuelle, en en créant une s'il n'y en a pas. |
| [RemoveNotesSlide](../../aspose.slides/notesslidemanager/removenotesslide)() | Supprime la diapositive de notes de la diapositive actuelle. |

### Exemples

L'exemple suivant montre comment ajouter des notes à une diapositive de présentation PowerPoint spécifique.

```csharp
[C#]
	// Instancier un objet Presentation qui représente un fichier de présentation
	using(Presentation presentation = new Presentation(dataDir + "AccessSlides.pptx")) {
	  // Ajouter des notes à la première diapositive
	  INotesSlideManager mgr = presentation.Slides[0].NotesSlideManager;
	  INotesSlide noteSlide = mgr.AddNotesSlide();
	  noteSlide.NotesTextFrame.Text = "Vos notes";
	  // Enregistrer la présentation sur le disque
	  presentation.Save(dataDir + "RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
	}
```

L'exemple suivant montre comment supprimer des notes d'une diapositive spécifique de présentation PowerPoint.

```csharp
[C#]
	// Instancier un objet Presentation qui représente un fichier de présentation
	using(Presentation presentation = new Presentation(dataDir + "AccessSlides.pptx")) {
	  // Supprimer les notes de la première diapositive
	  INotesSlideManager mgr = presentation.Slides[0].NotesSlideManager;
	  mgr.RemoveNotesSlide();
	  // Enregistrer la présentation sur le disque
	  presentation.Save(dataDir + "RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
	}
```

### Voir aussi

* classe [DomObject&lt;TParent&gt;](../domobject-1)
* classe [Slide](../slide)
* interface [INotesSlideManager](../inotesslidemanager)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->