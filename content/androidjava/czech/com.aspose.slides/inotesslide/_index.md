---
title: INotesSlide
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje snímek poznámek v prezentaci.
type: docs
url: /cs/com.aspose.slides/inotesslide/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Představuje snímek poznámek v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter snímku poznámek. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Vrací TextFrame s textem poznámek, pokud existuje. |
| [getParentSlide()](#getParentSlide--) | Vrací ParentSlide pouze pro čtení [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter snímku poznámek. Pouze pro čtení [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

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

Vrací ParentSlide pouze pro čtení [ISlide](../../com.aspose.slides/islide).

**Vrací:**
[ISlide](../../com.aspose.slides/islide)