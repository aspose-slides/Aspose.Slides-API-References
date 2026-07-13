---
title: ILayoutSlide
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta una diapositiva di layout.
type: docs
url: /it/com.aspose.slides/ilayoutslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Rappresenta una diapositiva di layout.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il gestore HeaderFooter della diapositiva di layout. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Restituisce il gestore dei segnaposto della diapositiva di layout. |
| [getMasterSlide()](#getMasterSlide--) | Restituisce o imposta la diapositiva master per un layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Restituisce o imposta la diapositiva master per un layout. |
| [getLayoutType()](#getLayoutType--) | Restituisce il tipo di layout di questa diapositiva di layout. |
| [hasDependingSlides()](#hasDependingSlides--) | Restituisce true se esiste almeno una diapositiva che dipende da questa diapositiva di layout. |
| [getDependingSlides()](#getDependingSlides--) | Restituisce un array con tutte le diapositive che dipendono da questa diapositiva di layout. |
| [remove()](#remove--) | Rimuove il layout dalla presentazione. |
| [getDrawingGuides()](#getDrawingGuides--) | Restituisce una collezione di guide di disegno per la diapositiva di layout. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Restituisce il gestore HeaderFooter della diapositiva di layout. Solo lettura [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Restituisce:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```


Restituisce il gestore dei segnaposto della diapositiva di layout. Solo lettura [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Restituisce:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


Restituisce o imposta la diapositiva master per un layout. Lettura/Scrittura [IMasterSlide](../../com.aspose.slides/imasterslide).

**Restituisce:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


Restituisce o imposta la diapositiva master per un layout. Lettura/Scrittura [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


Restituisce il tipo di layout di questa diapositiva di layout. Solo lettura [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Restituisce:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Restituisce true se esiste almeno una diapositiva che dipende da questa diapositiva di layout. Solo lettura boolean.

**Restituisce:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Restituisce un array con tutte le diapositive che dipendono da questa diapositiva di layout.

**Restituisce:**
com.aspose.slides.ISlide[] - Array with all slides, which depend on this layout slide
### remove() {#remove--}
```
public abstract void remove()
```


Rimuove il layout dalla presentazione.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Restituisce una collezione di guide di disegno per la diapositiva di layout. Solo lettura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Aggiunta della nuova guida di disegno verticale a sinistra del centro della diapositiva
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)