---
title: NotesSlide
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una diapositiva delle note in una presentazione.
type: docs
url: /it/com.aspose.slides/notesslide/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tutte le interfacce implementate:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Rappresenta una diapositiva delle note in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il manager HeaderFooter della diapositiva delle note. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Restituisce un TextFrame con il testo delle note, se presente. |
| [getThemeManager()](#getThemeManager--) | Restituisce il gestore del tema di override. |
| [getParentSlide()](#getParentSlide--) | Restituisce la diapositiva genitore. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifica se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifica se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Restituisce il manager HeaderFooter della diapositiva delle note. Solo lettura [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

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

Restituisce il gestore del tema di override. Solo lettura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Restituisce:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Restituisce la diapositiva genitore. Solo lettura [ISlide](../../com.aspose.slides/islide).

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Specifica se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Specifica se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |