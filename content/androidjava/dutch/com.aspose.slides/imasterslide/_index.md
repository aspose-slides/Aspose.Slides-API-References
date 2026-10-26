---
title: IMasterSlide
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een masterdia in een presentatie voor.
type: docs
url: /nl/com.aspose.slides/imasterslide/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Stelt een masterdia in een presentatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert de HeaderFooter manager van de masterdia. |
| [getTitleStyle()](#getTitleStyle--) | Retourneert de stijl van een titeltekst. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Maakt een nieuwe masterdia op basis van de huidige, past een extern thema toe en past de gemaakte masterdia toe op alle afhankelijke dia's. |
| [getBodyStyle()](#getBodyStyle--) | Retourneert de stijl van een body-tekst. |
| [getOtherStyle()](#getOtherStyle--) | Retourneert de stijl van een andere tekst. |
| [getLayoutSlides()](#getLayoutSlides--) | Retourneert de verzameling van kind-layoutdia's voor deze masterdia. |
| [getPreserve()](#getPreserve--) | Bepaalt of de bijbehorende master wordt verwijderd wanneer alle dia's die op die master volgen, worden verwijderd. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Bepaalt of de bijbehorende master wordt verwijderd wanneer alle dia's die op die master volgen, worden verwijderd. |
| [hasDependingSlides()](#hasDependingSlides--) | Retourneert true als er minstens één dia bestaat die van deze masterdia afhankelijk is. |
| [getDependingSlides()](#getDependingSlides--) | Retourneert een array met alle dia's die van deze masterdia afhankelijk zijn. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een verzameling van teken-gidsen voor de masterdia. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Retourneert de HeaderFooter manager van de masterdia. Alleen-lezen [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Retour:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Retourneert de stijl van een titeltekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retour:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Maakt een nieuwe masterdia op basis van de huidige, past een extern thema toe en past de gemaakte masterdia toe op alle afhankelijke dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het externe themabestand (.thmx). |

**Retour:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nieuwe gethematiseerde MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Retourneert de stijl van een body-tekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retour:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Retourneert de stijl van een andere tekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retour:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Retourneert de verzameling van kind-layoutdia's voor deze masterdia. Alleen-lezen [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

U kunt toegang krijgen tot een alternatieve API voor het toevoegen/invoegen/verwijderen/kopiëren van layoutdia's via de eigenschap ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Retour:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Bepaalt of de bijbehorende master wordt verwijderd wanneer alle dia's die op die master volgen, worden verwijderd. Opmerking: Aspose.Slides zal nooit zelf een ongebruikt master verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roep [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) aan. Lezen/Schrijven boolean.

**Retour:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Bepaalt of de bijbehorende master wordt verwijderd wanneer alle dia's die op die master volgen, worden verwijderd. Opmerking: Aspose.Slides zal nooit zelf een ongebruikt master verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roep [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) aan. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Retourneert true als er minstens één dia bestaat die van deze masterdia afhankelijk is. Alleen-lezen boolean.

**Retour:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Retourneert een array met alle dia's die van deze masterdia afhankelijk zijn.

**Retour:**
com.aspose.slides.ISlide[] - Array van [ISlide](../../com.aspose.slides/islide), die van deze masterdia afhankelijk zijn
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Retourneert een verzameling van teken-gidsen voor de masterdia. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Voegt de nieuwe verticale teken-gids toe rechts van het midden van de dia
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)