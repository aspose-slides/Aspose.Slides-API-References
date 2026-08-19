---
title: MasterSlide
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una master slide in una presentazione.
type: docs
url: /it/com.aspose.slides/masterslide/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Rappresenta una master slide in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il manager HeaderFooter della master slide. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Crea una nuova master slide basata su quella corrente, applicando un tema esterno e applica la master slide creata a tutte le slide dipendenti. |
| [getTitleStyle()](#getTitleStyle--) | Restituisce lo stile di un testo titolo. |
| [getBodyStyle()](#getBodyStyle--) | Restituisce lo stile di un testo corpo. |
| [getOtherStyle()](#getOtherStyle--) | Restituisce lo stile di un altro testo. |
| [getLayoutSlides()](#getLayoutSlides--) | Restituisce la collezione di layout slide figlie per questa master slide. |
| [getPreserve()](#getPreserve--) | Determina se la master corrispondente viene eliminata quando tutte le slide che seguono quella master vengono eliminate. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Determina se la master corrispondente viene eliminata quando tutte le slide che seguono quella master vengono eliminate. |
| [getDependingSlides()](#getDependingSlides--) | Restituisce un array con tutte le slide che dipendono da questa master slide. |
| [hasDependingSlides()](#hasDependingSlides--) | Restituisce true se esiste almeno una slide che dipende da questa master slide. |
| [getThemeManager()](#getThemeManager--) | Restituisce il gestore del tema. |
| [getName()](#getName--) | Restituisce o imposta il nome di una master slide. |
| [setName(String value)](#setName-java.lang.String-) | Restituisce o imposta il nome di una master slide. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifica se le forme sulla master slide devono essere mostrate sulle slide o no. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifica se le forme sulla master slide devono essere mostrate sulle slide o no. |
| [getDrawingGuides()](#getDrawingGuides--) | Restituisce una collezione di guide di disegno per la master slide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Restituisce il manager HeaderFooter della master slide. Sola lettura [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Restituisce:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


Crea una nuova master slide basata su quella corrente, applicando un tema esterno e applica la master slide creata a tutte le slide dipendenti.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso al file tema esterno (.thmx). |

**Restituisce:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nuova MasterSlide temata.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```


Restituisce lo stile di un testo titolo. Sola lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```


Restituisce lo stile di un testo corpo. Sola lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```


Restituisce lo stile di un altro testo. Sola lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```


Restituisce la collezione di layout slide figlie per questa master slide. Sola lettura [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

È possibile accedere all'API alternativa per aggiungere/inserire/rimuovere/duplicare layout slide usando la proprietà ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Restituisce:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```


Determina se la master corrispondente viene eliminata quando tutte le slide che seguono quella master vengono eliminate. Nota: Aspose.Slides non rimuoverà mai una master non utilizzata da solo; per rimuovere realmente le master non utilizzate chiamare [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lettura/scrittura  boolean .

**Restituisce:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```


Determina se la master corrispondente viene eliminata quando tutte le slide che seguono quella master vengono eliminate. Nota: Aspose.Slides non rimuoverà mai una master non utilizzata da solo; per rimuovere realmente le master non utilizzate chiamare [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lettura/scrittura  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Restituisce un array con tutte le slide che dipendono da questa master slide.

**Restituisce:**
com.aspose.slides.ISlide[] - Array di [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Restituisce true se esiste almeno una slide che dipende da questa master slide. Sola lettura  boolean .

**Restituisce:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Restituisce il gestore del tema. Sola lettura [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Restituisce:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```


Restituisce o imposta il nome di una master slide. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Restituisce o imposta il nome di una master slide. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specifica se le forme sulla master slide devono essere mostrate sulle slide o no. Per la master slide stessa questa proprietà restituisce sempre false. Lettura/scrittura  boolean .

**Restituisce:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specifica se le forme sulla master slide devono essere mostrate sulle slide o no. Per la master slide stessa questa proprietà restituisce sempre false. Lettura/scrittura  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Restituisce una collezione di guide di disegno per la master slide. Sola lettura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Aggiunta della nuova guida di disegno verticale a destra del centro della slide
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)