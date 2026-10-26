---
title: IMasterSlide
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en masterbild i en presentation.
type: docs
url: /sv/com.aspose.slides/imasterslide/
---
**Alla implementerade gränssnitt:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Representerar en masterbild i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter manager för masterbilden. |
| [getTitleStyle()](#getTitleStyle--) | Returnerar stilen för en titeltext. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Skapar en ny masterbild baserad på den nuvarande, applicerar ett externt tema på den och tillämpar den skapade masterbilden på alla beroende bilder. |
| [getBodyStyle()](#getBodyStyle--) | Returnerar stilen för en brödtext. |
| [getOtherStyle()](#getOtherStyle--) | Returnerar stilen för en övrig text. |
| [getLayoutSlides()](#getLayoutSlides--) | Returnerar samlingen av underordnade layoutbilder för denna masterbild. |
| [getPreserve()](#getPreserve--) | Avgör om den motsvarande master-bilden tas bort när alla bilder som följer den master-bilden har tagits bort. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Avgör om den motsvarande master-bilden tas bort när alla bilder som följer den master-bilden har tagits bort. |
| [hasDependingSlides()](#hasDependingSlides--) | Returnerar true om det finns minst en bild som är beroende av denna masterbild. |
| [getDependingSlides()](#getDependingSlides--) | Returnerar en array med alla bilder, som är beroende av denna masterbild. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar en samling av ritningsguider för masterbilden. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter manager för masterbilden. Skrivskyddad [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

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

Skapar en ny masterbild baserad på den nuvarande, applicerar ett externt tema på den och tillämpar den skapade masterbilden på alla beroende bilder.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den externa temafil (.thmx). |

**Returnerar:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Ny tematiserad MasterSlide.
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

Returnerar stilen för en övrig text. Skrivskyddad [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Returnerar samlingen av underordnade layoutbilder för masterbilden. Skrivskyddad [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Du kan komma åt ett alternativt API för att lägga till/infoga/ta bort/klona layoutbilder genom att använda egenskapen ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Returnerar:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Avgör om den motsvarande master-bilden tas bort när alla bilder som följer den master-bilden har tagits bort. Obs: Aspose.Slides kommer aldrig att ta bort någon oanvänd master automatiskt; för att faktiskt ta bort oanvända master-bilder anropa [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Läs/skriv boolesk.

**Returnerar:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Avgör om den motsvarande master-bilden tas bort när alla bilder som följer den master-bilden har tagits bort. Obs: Aspose.Slides kommer aldrig att ta bort någon oanvänd master automatiskt; för att faktiskt ta bort oanvända master-bilder anropa [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Returnerar true om det finns minst en bild som är beroende av denna masterbild. Skrivskyddad boolesk.

**Returnerar:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Returnerar en array med alla bilder som är beroende av denna masterbild.

**Returnerar:**
com.aspose.slides.ISlide[] - Array av [ISlide](../../com.aspose.slides/islide), som är beroende av denna masterbild
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Returnerar en samling av ritningsguider för masterbilden. Skrivskyddad [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Lägger till den nya vertikala ritningsguiden till höger om bildens centrum
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)