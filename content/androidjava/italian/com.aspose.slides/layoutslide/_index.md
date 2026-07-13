---
title: LayoutSlide
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta una diapositiva di layout.
type: docs
url: /it/com.aspose.slides/layoutslide/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tutte le interfacce implementate:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Rappresenta una diapositiva di layout.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il manager HeaderFooter della diapositiva di layout. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Restituisce il manager placeholder della diapositiva di layout. |
| [getMasterSlide()](#getMasterSlide--) | Restituisce o imposta la diapositiva master per un layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Restituisce o imposta la diapositiva master per un layout. |
| [remove()](#remove--) | Rimuove il layout dalla presentazione. |
| [getThemeManager()](#getThemeManager--) | Restituisce il manager del tema sovrascrivente. |
| [getLayoutType()](#getLayoutType--) | Restituisce il tipo di layout di questa diapositiva di layout. |
| [getDependingSlides()](#getDependingSlides--) | Restituisce un array con tutte le diapositive che dipendono da questa diapositiva di layout. |
| [hasDependingSlides()](#hasDependingSlides--) | Restituisce true se esiste almeno una diapositiva che dipende da questa diapositiva di layout. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. |
| [getDrawingGuides()](#getDrawingGuides--) | Restituisce una collezione di guide di disegno per la diapositiva di layout. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Restituisce il manager HeaderFooter della diapositiva di layout. Solo lettura [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Restituisce:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Restituisce il manager placeholder della diapositiva di layout. Solo lettura [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Restituisce:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

Restituisce o imposta la diapositiva master per un layout. Lettura/scrittura [IMasterSlide](../../com.aspose.slides/imasterslide).

**Restituisce:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

Restituisce o imposta la diapositiva master per un layout. Lettura/scrittura [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```

Rimuove il layout dalla presentazione.
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Restituisce il manager del tema sovrascrivente. Solo lettura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Restituisce:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

Restituisce il tipo di layout di questa diapositiva di layout. Solo lettura [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Restituisce:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Restituisce un array con tutte le diapositive che dipendono da questa diapositiva di layout.

**Restituisce:**
com.aspose.slides.ISlide[] - Array di [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Restituisce true se esiste almeno una diapositiva che dipende da questa diapositiva di layout. Solo lettura boolean.

**Restituisce:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
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