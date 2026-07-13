---
title: MasterHandoutSlide
second_title: Aspose.Slides per Android tramite il riferimento API Java
description: Rappresenta la diapositiva master per le dispense.
type: docs
url: /it/com.aspose.slides/masterhandoutslide/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Rappresenta la diapositiva master per le dispense.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifica se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifica se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il manager HeaderFooter della diapositiva master per le dispense. |
| [getThemeManager()](#getThemeManager--) | Restituisce il manager del tema. |
| [getDrawingGuides()](#getDrawingGuides--) | Restituisce una collezione di guide di disegno per la diapositiva master per le dispense. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Specifică se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre false. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Specifică se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre false. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Restituisce il manager HeaderFooter della diapositiva master per le dispense. Sola lettura [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Restituisce:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Restituisce il manager del tema. Sola lettura [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Restituisce:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Restituisce una collezione di guide di disegno per la diapositiva master per le dispense. Sola lettura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Aggiunta della nuova guida di disegno orizzontale sopra il centro della diapositiva
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)