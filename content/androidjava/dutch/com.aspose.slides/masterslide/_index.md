---
title: MasterSlide
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een master slide in een presentatie voor.
type: docs
url: /nl/com.aspose.slides/masterslide/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Stelt een master-slide in een presentatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert de HeaderFooter manager van de master slide. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Maakt een nieuwe master slide op basis van de huidige, past er een extern thema op toe en past de gemaakte master slide toe op alle afhankelijke slides. |
| [getTitleStyle()](#getTitleStyle--) | Retourneert de stijl van een titeltekst. |
| [getBodyStyle()](#getBodyStyle--) | Retourneert de stijl van een body-tekst. |
| [getOtherStyle()](#getOtherStyle--) | Retourneert de stijl van een andere tekst. |
| [getLayoutSlides()](#getLayoutSlides--) | Retourneert de collectie van child-layout-slides voor deze master slide. |
| [getPreserve()](#getPreserve--) | Bepaalt of de overeenkomstige master wordt verwijderd wanneer alle slides die de master volgen, zijn verwijderd. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Bepaalt of de overeenkomstige master wordt verwijderd wanneer alle slides die de master volgen, zijn verwijderd. |
| [getDependingSlides()](#getDependingSlides--) | Retourneert een array met alle slides die afhankelijk zijn van deze master slide. |
| [hasDependingSlides()](#hasDependingSlides--) | Retourneert true als er ten minste één slide bestaat die afhankelijk is van deze master slide. |
| [getThemeManager()](#getThemeManager--) | Retourneert de theme manager. |
| [getName()](#getName--) | Retourneert of stelt de naam van een master slide in. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert of stelt de naam van een master slide in. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specificeert of vormen op de master slide al dan niet getoond moeten worden op slides. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specificeert of vormen op de master slide al dan niet getoond moeten worden op slides. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een collectie van tekengidsen voor de master slide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Retourneert de HeaderFooter manager van de master slide. Alleen-lezen [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Retourneert:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Maakt een nieuwe master slide op basis van de huidige, past een extern thema toe en past de gemaakte master slide toe op alle afhankelijke slides.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het externe themabestand (.thmx). |

**Retourneert:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nieuwe gethematiseerde MasterSlide.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Retourneert de stijl van een titeltekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Retourneert de stijl van een body-tekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Retourneert de stijl van een andere tekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Retourneert de collectie van child-layout-slides voor deze master slide. Alleen-lezen [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

U kunt toegang krijgen tot een alternatieve API voor het toevoegen/invoegen/verwijderen/kopiëren van layout-slides via de eigenschap ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) property.

**Retourneert:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Bepaalt of de overeenkomstige master wordt verwijderd wanneer alle slides die de master volgen, zijn verwijderd. Opmerking: Aspose.Slides zal nooit zelf een ongebruikte master verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roep [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) aan. Lezen/Schrijven boolean .

**Retourneert:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Bepaalt of de overeenkomstige master wordt verwijderd wanneer alle slides die de master volgen, zijn verwijderd. Opmerking: Aspose.Slides zal nooit zelf een ongebruikte master verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roep [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) aan. Lezen/Schrijven boolean .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Retourneert een array met alle slides die afhankelijk zijn van deze master slide.

**Retourneert:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Retourneert true als er ten minste één slide bestaat die afhankelijk is van deze master slide. Alleen-lezen boolean .

**Retourneert:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Retourneert de theme manager. Alleen-lezen [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Retourneert:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Retourneert of stelt de naam van een master slide in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Retourneert of stelt de naam van een master slide in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Specificeert of vormen op de master slide al dan niet getoond moeten worden op slides. Voor de master slide zelf geeft deze eigenschap altijd false terug. Lezen/Schrijven boolean .

**Retourneert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Specificeert of vormen op de master slide al dan niet getoond moeten worden op slides. Voor de master slide zelf geeft deze eigenschap altijd false terug. Lezen/Schrijven boolean .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Retourneert een collectie van tekengidsen voor de master slide. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Toevoegen van de nieuwe verticale tekengids rechts van het midden van de slide
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)