---
title: INotesSlide
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Notizfolie in einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/inotesslide/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Stellt eine Notizfolie in einer Präsentation dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Notizfolie zurück. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Gibt ein TextFrame mit dem Text der Notizen zurück, falls vorhanden. |
| [getParentSlide()](#getParentSlide--) | Gibt ein ParentSlide Read-only [ISlide](../../com.aspose.slides/islide) zurück. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Notizfolie zurück. Read-only [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Rückgabe:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Gibt ein TextFrame mit dem Text der Notizen zurück, falls vorhanden. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Gibt ein ParentSlide Read-only [ISlide](../../com.aspose.slides/islide) zurück.

**Rückgabe:**
[ISlide](../../com.aspose.slides/islide)