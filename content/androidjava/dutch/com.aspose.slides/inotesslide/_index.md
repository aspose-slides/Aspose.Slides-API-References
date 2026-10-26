---
title: INotesSlide
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een notitieslide in een presentatie voor.
type: docs
url: /nl/com.aspose.slides/inotesslide/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Stelt een notitieslide in een presentatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert HeaderFooter manager van de notitieslide. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Retourneert een TextFrame met de notitietekst indien aanwezig. |
| [getParentSlide()](#getParentSlide--) | Retourneert een ParentSlide Alleen-lezen [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Retourneert HeaderFooter manager van de notitieslide. Alleen-lezen [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Retour:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Retourneert een TextFrame met de notitietekst indien aanwezig. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Retourneert een ParentSlide Alleen-lezen [ISlide](../../com.aspose.slides/islide).

**Retour:**
[ISlide](../../com.aspose.slides/islide)