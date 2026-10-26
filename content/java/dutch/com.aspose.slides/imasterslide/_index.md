---
title: IMasterSlide
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een masterslide voor in een presentatie.
type: docs
url: /nl/com.aspose.slides/imasterslide/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Stelt een masterslide voor in een presentatie.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert HeaderFooter manager van de masterslide. |
| [getTitleStyle()](#getTitleStyle--) | Retourneert de stijl van een titeltekst. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Creëert een nieuwe masterslide op basis van de huidige, past een extern thema toe en past de gemaakte masterslide toe op alle afhankelijke dia's. |
| [getBodyStyle()](#getBodyStyle--) | Retourneert de stijl van een bodytekst. |
| [getOtherStyle()](#getOtherStyle--) | Retourneert de stijl van een andere tekst. |
| [getLayoutSlides()](#getLayoutSlides--) | Retourneert de collectie van kindlayoutdia's voor deze masterslide. |
| [getPreserve()](#getPreserve--) | Bepaalt of de overeenkomstige master wordt verwijderd wanneer alle dia's die die master volgen, worden verwijderd. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Bepaalt of de overeenkomstige master wordt verwijderd wanneer alle dia's die die master volgen, worden verwijderd. |
| [hasDependingSlides()](#hasDependingSlides--) | Retourneert true als er ten minste één dia bestaat die afhankelijk is van deze masterslide. |
| [getDependingSlides()](#getDependingSlides--) | Retourneert een array met alle dia's die afhankelijk zijn van deze masterslide. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een collectie van tekengidsen voor de masterslide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Retourneert HeaderFooter manager van de masterslide. Alleen-lezen [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Retourneert:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```


Retourneert de stijl van een titeltekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


Creëert een nieuwe masterslide op basis van de huidige, past een extern thema toe en past de gemaakte masterslide toe op alle afhankelijke dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het externe themabestand (.thmx). |

**Retourneert:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nieuwe thematische MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```


Retourneert de stijl van een bodytekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```


Retourneert de stijl van een andere tekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```


Retourneert de collectie van kindlayoutdia's voor deze masterslide. Alleen-lezen [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

U kunt toegang krijgen tot de alternatieve API voor het toevoegen/invoegen/verwijderen/kopiëren van layout-dia's door de eigenschap ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) te gebruiken.

**Retourneert:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```


Bepaalt of de overeenkomstige master wordt verwijderd wanneer alle dia's die die master volgen, worden verwijderd. Opmerking: Aspose.Slides zal nooit zelf een ongebruikte master verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roep [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) aan. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```


Bepaalt of de overeenkomstige master wordt verwijderd wanneer alle dia's die die master volgen, worden verwijderd. Opmerking: Aspose.Slides zal nooit zelf een ongebruikte master verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roep [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) aan. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Retourneert true als er ten minste één dia bestaat die afhankelijk is van deze masterslide. Alleen-lezen boolean.

**Retourneert:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Retourneert een array met alle dia's die afhankelijk zijn van deze masterslide.

**Retourneert:**
com.aspose.slides.ISlide[] - Array van [ISlide](../../com.aspose.slides/islide), die afhankelijk zijn van deze masterslide
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Retourneert een collectie van tekengidsen voor de masterslide. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Voeg de nieuwe verticale tekengids toe aan de rechterkant van het midden van de dia
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)