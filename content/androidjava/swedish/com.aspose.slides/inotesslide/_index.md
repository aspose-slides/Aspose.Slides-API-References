---
title: INotesSlide
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en anteckningsbild i en presentation.
type: docs
url: /sv/com.aspose.slides/inotesslide/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Representerar en anteckningsbild i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter manager för anteckningsbilden. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Returnerar en TextFrame med anteckningarnas text om det finns någon. |
| [getParentSlide()](#getParentSlide--) | Returnerar en ParentSlide Endast läsning [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter manager för anteckningsbilden. Endast läsning [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Returnerar:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Returnerar en TextFrame med anteckningarnas text om det finns någon. Endast läsning [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Returnerar en ParentSlide Endast läsning [ISlide](../../com.aspose.slides/islide).

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)