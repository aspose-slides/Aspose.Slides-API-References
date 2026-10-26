---
title: INotesSlide
second_title: Aspose.Slides pro Java - reference API
description: Představuje poznámkový snímek v prezentaci.
type: docs
url: /cs/com.aspose.slides/inotesslide/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Reprezentuje poznámkový snímek v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter poznámkového snímku. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Vrací TextFrame s textem poznámek, pokud existuje. |
| [getParentSlide()](#getParentSlide--) | Vrací ParentSlide Pouze pro čtení [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter poznámkového snímku. Pouze pro čtení [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Vrací:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Vrací TextFrame s textem poznámek, pokud existuje. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Vrací ParentSlide Pouze pro čtení [ISlide](../../com.aspose.slides/islide).

**Vrací:**
[ISlide](../../com.aspose.slides/islide)