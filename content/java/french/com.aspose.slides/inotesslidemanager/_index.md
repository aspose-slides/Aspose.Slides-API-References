---
title: INotesSlideManager
second_title: Aspose.Slides for Java API Reference
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
| [getNotesSlide()](#getNotesSlide--) | Retourne la notes slide pour la slide actuelle. |
| [addNotesSlide()](#addNotesSlide--) | Retourne la notes slide pour la slide actuelle, en créant une si elle n'existe pas. |
| [removeNotesSlide()](#removeNotesSlide--) | Supprime la notes slide de la slide actuelle. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Renvoie la notes slide pour la slide actuelle. Retourne null si la slide n'a pas de notes slide. Lecture seule [INotesSlide](../../com.aspose.slides/inotesslide).

**Renvoie :**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Renvoie la notes slide pour la slide actuelle, en créant une si elle n'existe pas.

**Renvoie :**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) pour cette slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Supprime la notes slide de la slide actuelle.