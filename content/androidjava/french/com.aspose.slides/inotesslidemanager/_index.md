---
title: INotesSlideManager
second_title: Aspose.Slides pour Android via la référence API Java
description: Gestionnaire de diapositive de notes.
type: docs
url: /fr/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Gestionnaire de diapositive de notes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Renvoie la diapositive de notes pour la diapositive actuelle. |
| [addNotesSlide()](#addNotesSlide--) | Renvoie la diapositive de notes pour la diapositive actuelle, en en créant une si elle n'existe pas. |
| [removeNotesSlide()](#removeNotesSlide--) | Supprime la diapositive de notes de la diapositive actuelle. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Renvoie la diapositive de notes pour la diapositive actuelle. Renvoie null si la diapositive n'a pas de diapositive de notes. Lecture seule [INotesSlide](../../com.aspose.slides/inotesslide).

**Renvoie :**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Renvoie la diapositive de notes pour la diapositive actuelle, en en créant une si elle n'existe pas.

**Renvoie :**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) pour cette diapositive.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Supprime la diapositive de notes de la diapositive actuelle.