---
title: NotesSlide
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una diapositiva delle note in una presentazione.
type: docs
url: /it/com.aspose.slides/notesslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Rappresenta una diapositiva delle note in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il gestore HeaderFooter della diapositiva delle note. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Restituisce un TextFrame con il testo delle note, se presente. |
| [getThemeManager()](#getThemeManager--) | Restituisce il gestore del tema sovrascrivente. |
| [getParentSlide()](#getParentSlide--) | Restituisce la diapositiva padre. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifica se le forme nella diapositiva master devono essere mostrate nelle diapositive o no. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifica se le forme nella diapositiva master devono essere mostrate nelle diapositive o no. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```


Restituisce il gestore HeaderFooter della diapositiva delle note. Solo lettura [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Restituisce:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```


Restituisce un TextFrame con il testo delle note, se presente. Solo lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Restituisce il gestore del tema sovrascrivente. Solo lettura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Restituisce:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```


Restituisce la diapositiva padre. Solo lettura [ISlide](../../com.aspose.slides/islide).

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specificа se le forme nella diapositiva master devono essere mostrate nelle diapositive o no. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specificа se le forme nella diapositiva master devono essere mostrate nelle diapositive o no. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |