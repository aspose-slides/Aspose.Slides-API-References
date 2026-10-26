---
title: IMasterSlide
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta una diapositiva master in una presentazione.
type: docs
url: /it/com.aspose.slides/imasterslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Rappresenta una diapositiva master in una presentazione.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il gestore HeaderFooter della diapositiva master. |
| [getTitleStyle()](#getTitleStyle--) | Restituisce lo stile di un testo titolo. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Crea una nuova diapositiva master basata su quella corrente, applicando un tema esterno e applica la diapositiva master creata a tutte le diapositive dipendenti. |
| [getBodyStyle()](#getBodyStyle--) | Restituisce lo stile di un testo del corpo. |
| [getOtherStyle()](#getOtherStyle--) | Restituisce lo stile di un altro testo. |
| [getLayoutSlides()](#getLayoutSlides--) | Restituisce la raccolta di diapositive layout figlie per questa diapositiva master. |
| [getPreserve()](#getPreserve--) | Determina se il master corrispondente viene eliminato quando tutte le diapositive che seguono quel master vengono eliminate. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Determina se il master corrispondente viene eliminato quando tutte le diapositive che seguono quel master vengono eliminate. |
| [hasDependingSlides()](#hasDependingSlides--) | Restituisce true se esiste almeno una diapositiva che dipende da questa diapositiva master. |
| [getDependingSlides()](#getDependingSlides--) | Restituisce un array con tutte le diapositive che dipendono da questa diapositiva master. |
| [getDrawingGuides()](#getDrawingGuides--) | Restituisce una raccolta di guide di disegno per la diapositiva master. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Restituisce il gestore HeaderFooter della diapositiva master. **Solo lettura** [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Restituisce:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Restituisce lo stile di un testo titolo. **Solo lettura** [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Crea una nuova diapositiva master basata su quella corrente, applicando un tema esterno e applica la diapositiva master creata a tutte le diapositive dipendenti.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso al file di tema esterno (.thmx). |

**Restituisce:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nuovo MasterSlide tematico.

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Restituisce lo stile di un testo del corpo. **Solo lettura** [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Restituisce lo stile di un altro testo. **Solo lettura** [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Restituisce la raccolta di diapositive layout figlie per questa diapositiva master. **Solo lettura** [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

È possibile accedere all'API alternativa per aggiungere/inserire/rimuovere/clonare le diapositive layout utilizzando la proprietà ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Restituisce:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Determina se il master corrispondente viene eliminato quando tutte le diapositive che seguono quel master vengono eliminate. Nota: Aspose.Slides non rimuoverà mai alcun master inutilizzato da solo; per rimuovere effettivamente i master inutilizzati chiamare [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) **Lettura/scrittura** boolean.

**Restituisce:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Determina se il master corrispondente viene eliminato quando tutte le diapositive che seguono quel master vengono eliminate. Nota: Aspose.Slides non rimuoverà mai alcun master inutilizzato da solo; per rimuovere effettivamente i master inutilizzati chiamare [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) **Lettura/scrittura** boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Restituisce true se esiste almeno una diapositiva che dipende da questa diapositiva master. **Solo lettura** boolean.

**Restituisce:**
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Restituisce un array con tutte le diapositive che dipendono da questa diapositiva master.

**Restituisce:**
com.aspose.slides.ISlide[] - Array di [ISlide](../../com.aspose.slides/islide), che dipendono da questa diapositiva master

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Restituisce una raccolta di guide di disegno per la diapositiva master. **Solo lettura** [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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