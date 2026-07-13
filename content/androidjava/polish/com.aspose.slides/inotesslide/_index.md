---
title: INotesSlide
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Reprezentuje slajd notatek w prezentacji.
type: docs
url: /pl/com.aspose.slides/inotesslide/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Reprezentuje slajd notatek w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera HeaderFooter slajdu notatek. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Zwraca obiekt TextFrame z tekstem notatek, jeżeli istnieje. |
| [getParentSlide()](#getParentSlide--) | Zwraca obiekt ParentSlide tylko do odczytu [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Zwraca menedżera HeaderFooter slajdu notatek. Tylko do odczytu [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Zwraca:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Zwraca obiekt TextFrame z tekstem notatek, jeżeli istnieje. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Zwraca obiekt ParentSlide tylko do odczytu [ISlide](../../com.aspose.slides/islide).

**Zwraca:**
[ISlide](../../com.aspose.slides/islide)