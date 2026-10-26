---
title: IMasterSlide
second_title: Aspose.Slides för Java API-referens
description: Representerar en master slide i en presentation.
type: docs
url: /sv/com.aspose.slides/imasterslide/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Representerar en master slide i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter-hanterare för master-sliden. |
| [getTitleStyle()](#getTitleStyle--) | Returnerar stilen för en titeltext. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Skapar en ny master slide baserad på den aktuella, applicerar ett externt tema på den och tillämpar den skapade master-sliden på alla beroende slides. |
| [getBodyStyle()](#getBodyStyle--) | Returnerar stilen för en brödtext. |
| [getOtherStyle()](#getOtherStyle--) | Returnerar stilen för en annan text. |
| [getLayoutSlides()](#getLayoutSlides--) | Returnerar samlingen av underordnade layout-slides för denna master slide. |
| [getPreserve()](#getPreserve--) | Bestämmer om motsvarande master tas bort när alla slides som följer den mastern har tagits bort. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Bestämmer om motsvarande master tas bort när alla slides som följer den mastern har tagits bort. |
| [hasDependingSlides()](#hasDependingSlides--) | Returnerar true om det finns minst en slide som är beroende av denna master slide. |
| [getDependingSlides()](#getDependingSlides--) | Returnerar en array med alla slides som är beroende av denna master slide. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar en samling av ritguider för master-sliden. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter-hanterare för master-sliden. Skrivskyddad [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Returnerar:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Returnerar stilen för en titeltext. Skrivskyddad [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Skapar en ny master slide baserad på den aktuella, applicerar ett externt tema på den och tillämpar den skapade master-sliden på alla beroende slides.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den externa temafil (.thmx). |

**Returnerar:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Ny tematisk MasterSlide.

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Returnerar stilen för en brödtext. Skrivskyddad [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Returnerar stilen för en annan text. Skrivskyddad [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Returnerar samlingen av underordnade layout-slides för denna master slide. Skrivskyddad [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Du kan komma åt ett alternativt API för att lägga till/infoga/ta bort/klona layout-slides genom att använda egenskapen ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) property.

**Returnerar:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Bestämmer om motsvarande master tas bort när alla slides som följer den mastern har tagits bort. Obs! Aspose.Slides kommer aldrig att automatiskt ta bort oanvända master-slides; för att faktiskt ta bort oanvända masters anropa [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Läs/skriv boolean.

**Returnerar:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Bestämmer om motsvarande master tas bort när alla slides som följer den mastern har tagits bort. Obs! Aspose.Slides kommer aldrig att automatiskt ta bort oanvända master-slides; för att faktiskt ta bort oanvända masters anropa [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Returnerar true om det finns minst en slide som är beroende av denna master slide. Skrivskyddad boolean.

**Returnerar:**
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Returnerar en array med alla slides som är beroende av denna master slide.

**Returnerar:**
com.aspose.slides.ISlide[] - Array av [ISlide](../../com.aspose.slides/islide), som är beroende av denna master slide

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Returnerar en samling av ritguider för master-sliden. Skrivskyddad [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Lägger till den nya vertikala ritguiden till höger om slide-centret
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)