---
title: INotesSlide
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una diapositiva di note in una presentazione.
type: docs
url: /it/com.aspose.slides/inotesslide/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Rappresenta una diapositiva di note in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il gestore HeaderFooter della diapositiva di note. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Restituisce un TextFrame con il testo delle note se presente. |
| [getParentSlide()](#getParentSlide--) | Restituisce un ParentSlide di sola lettura [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```


Restituisce il gestore HeaderFooter della diapositiva di note. Di sola lettura [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Restituisce:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```


Restituisce un TextFrame con il testo delle note se presente. Di sola lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```


Restituisce un ParentSlide di sola lettura [ISlide](../../com.aspose.slides/islide).

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)