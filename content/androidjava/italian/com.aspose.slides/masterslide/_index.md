---
title: MasterSlide
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una diapositiva master in una presentazione.
type: docs
url: /it/com.aspose.slides/masterslide/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Rappresenta una diapositiva master in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il gestore HeaderFooter della diapositiva master. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Crea una nuova diapositiva master basata su quella corrente, applicando un tema esterno e applica la diapositiva master creata a tutte le diapositive dipendenti. |
| [getTitleStyle()](#getTitleStyle--) | Restituisce lo stile di un testo di titolo. |
| [getBodyStyle()](#getBodyStyle--) | Restituisce lo stile di un testo del corpo. |
| [getOtherStyle()](#getOtherStyle--) | Restituisce lo stile di un altro testo. |
| [getLayoutSlides()](#getLayoutSlides--) | Restituisce la raccolta di diapositive di layout figlie per questa diapositiva master. |
| [getPreserve()](#getPreserve--) | Determina se il master corrispondente viene eliminato quando tutte le diapositive che seguono quel master vengono eliminate. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Determina se il master corrispondente viene eliminato quando tutte le diapositive che seguono quel master vengono eliminate. |
| [getDependingSlides()](#getDependingSlides--) | Restituisce un array con tutte le diapositive che dipendono da questa diapositiva master. |
| [hasDependingSlides()](#hasDependingSlides--) | Restituisce true se esiste almeno una diapositiva che dipende da questa diapositiva master. |
| [getThemeManager()](#getThemeManager--) | Restituisce il gestore del tema. |
| [getName()](#getName--) | Restituisce o imposta il nome di una diapositiva master. |
| [setName(String value)](#setName-java.lang.String-) | Restituisce o imposta il nome di una diapositiva master. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. |
| [getDrawingGuides()](#getDrawingGuides--) | Restituisce una raccolta di guide di disegno per la diapositiva master. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Restituisce il gestore HeaderFooter della diapositiva master. Solo lettura [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Restituisce:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Crea una nuova diapositiva master basata su quella corrente, applicando un tema esterno e applica la diapositiva master creata a tutte le diapositive dipendenti.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file del tema esterno (.thmx). |

**Restituisce:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nuovo MasterSlide tematico.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Restituisce lo stile di un testo di titolo. Solo lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Restituisce lo stile di un testo del corpo. Solo lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Restituisce lo stile di un altro testo. Solo lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Restituisce la raccolta di diapositive di layout figlie per questa diapositiva master. Solo lettura [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

È possibile accedere a un'API alternativa per aggiungere/inserire/rimuovere/clonare diapositive di layout utilizzando la proprietà ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) .

**Restituisce:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Determina se il master corrispondente viene eliminato quando tutte le diapositive che seguono quel master vengono eliminate. Nota: Aspose.Slides non rimuoverà mai alcun master inutilizzato da solo; per rimuovere effettivamente i master inutilizzati chiamare [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lettura/scrittura  boolean .

**Restituisce:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Determina se il master corrispondente viene eliminato quando tutte le diapositive che seguono quel master vengono eliminate. Nota: Aspose.Slides non rimuoverà mai alcun master inutilizzato da solo; per rimuovere effettivamente i master inutilizzati chiamare [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lettura/scrittura  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Restituisce un array con tutte le diapositive che dipendono da questa diapositiva master.

**Restituisce:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Restituisce true se esiste almeno una diapositiva che dipende da questa diapositiva master. Solo lettura  boolean .

**Restituisce:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Restituisce il gestore del tema. Solo lettura [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Restituisce:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Restituisce o imposta il nome di una diapositiva master. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Restituisce o imposta il nome di una diapositiva master. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre false. Lettura/scrittura  boolean .

**Restituisce:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre false. Lettura/scrittura  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Restituisce una raccolta di guide di disegno per la diapositiva master. Solo lettura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Aggiunta della nuova guida di disegno verticale a destra del centro della diapositiva
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)