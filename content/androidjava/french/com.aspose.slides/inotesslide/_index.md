---
title: INotesSlide
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une diapositive de notes dans une présentation.
type: docs
url: /fr/com.aspose.slides/inotesslide/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Représente une diapositive de notes dans une présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive de notes. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Renvoie un TextFrame contenant le texte des notes, le cas échéant. |
| [getParentSlide()](#getParentSlide--) | Renvoie un ParentSlide en lecture seule [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la diapositive de notes. Lecture seule [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Renvoie:**  
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Renvoie un TextFrame contenant le texte des notes, le cas échéant. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

**Renvoie:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Renvoie un ParentSlide en lecture seule [ISlide](../../com.aspose.slides/islide).

**Renvoie:**  
[ISlide](../../com.aspose.slides/islide)