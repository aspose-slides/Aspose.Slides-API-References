---
title: MasterNotesSlide
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta la diapositiva master per le note.
type: docs
url: /it/com.aspose.slides/masternotesslide/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Rappresenta la diapositiva master per le note.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il gestore HeaderFooter della diapositiva master delle note. |
| [getThemeManager()](#getThemeManager--) | Restituisce il gestore del tema. |
| [getNotesStyle()](#getNotesStyle--) | Restituisce lo stile di un testo delle note. |
| [getDrawingGuides()](#getDrawingGuides--) | Restituisce una collezione di guide di disegno per la diapositiva master delle note. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre false. Booleano di lettura/scrittura.

**Restituisce:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre false. Booleano di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


Restituisce il gestore HeaderFooter della diapositiva master delle note. Sola lettura [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Restituisce:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Restituisce il gestore del tema. Sola lettura [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Restituisce:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```


Restituisce lo stile di un testo delle note. Sola lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Restituisce una collezione di guide di disegno per la diapositiva master delle note. Sola lettura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Aggiunge la nuova guida di disegno orizzontale sotto il centro della diapositiva
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)