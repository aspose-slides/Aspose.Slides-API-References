---
title: NotesSlide
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een notitieslide in een presentatie voor.
type: docs
url: /nl/com.aspose.slides/notesslide/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Stelt een notitieslide in een presentatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert HeaderFooter manager van de notitieslide. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Retourneert een TextFrame met de tekst van notities als die er is. |
| [getThemeManager()](#getThemeManager--) | Retourneert de overschreven theme manager. |
| [getParentSlide()](#getParentSlide--) | Retourneert de bovenliggende slide. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Geeft aan of vormen op de masterslide al dan niet getoond moeten worden op slides. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Geeft aan of vormen op de masterslide al dan niet getoond moeten worden op slides. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Retourneert HeaderFooter manager van de notitieslide. Alleen-lezen [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Retour:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Retourneert een TextFrame met de tekst van notities als die er is. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Retourneert de overschreven theme manager. Alleen-lezen [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Retour:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Retourneert de bovenliggende slide. Alleen-lezen [ISlide](../../com.aspose.slides/islide).

**Retour:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Geeft aan of vormen op de masterslide al dan niet getoond moeten worden op slides. Lezen/Schrijven boolean.

**Retour:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Geeft aan of vormen op de masterslide al dan niet getoond moeten worden op slides. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |