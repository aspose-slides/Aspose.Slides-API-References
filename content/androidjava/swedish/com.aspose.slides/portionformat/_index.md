---
title: PortionFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Denna klass innehåller formateringsegenskaperna för textdelen.
type: docs
url: /sv/com.aspose.slides/portionformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Denna klass innehåller formateringsegenskaperna för textdelarna. Till skillnad från [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Instansiera ett presentationsobjekt som representerar en presentationsfil
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides använder dessa speciella identifierare (liknande de som används i PowerPoint):
>      // +mn-lt - Kroppstextfont Latin (Minor Latin Font)
>      // +mj-lt - Rubrikfont Latin (Major Latin Font)
>      // +mn-ea - Kroppstextfont Östasiatisk (Minor East Asian Font)
>      // +mj-ea - Kroppstextfont Östasiatisk (Minor East Asian Font)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Denna klass används för att returnera och manipulera formateringsegenskaperna för textdelar som definierats för den specifika delen. Detta innebär att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "undefined".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda metoden [getEffective](../../com.aspose.slides/portionformat\#getEffective) som returnerar en [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) instans.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Initialiserar en ny instans av klassen [PortionFormat](../../com.aspose.slides/portionformat). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Returnerar eller sätter bokmärkesidentifierare. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Returnerar eller sätter bokmärkesidentifierare. |
| [getSmartTagClean()](#getSmartTagClean--) | Avgör om smarttaggen ska rensas. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Avgör om smarttaggen ska rensas. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Returnerar eller sätter hyperlänken som definierats för musklick. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Returnerar eller sätter hyperlänken som definierats för musklick. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Returnerar eller sätter hyperlänken som definierats för mus över. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Returnerar eller sätter hyperlänken som definierats för mus över. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Hyperlänkhanteerare. |
| [getEffective()](#getEffective--) | Hämtar effektiva formateringsdata för delen med arv tillämpat. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```


Initialiserar en ny instans av klassen [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```


Returnerar eller sätter bokmärkesidentifierare. Läs/skriv String.

**Returns:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```


Returnerar eller sätter bokmärkesidentifierare. Läs/skriv String.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```


Avgör om smarttaggen ska rensas. Inget arv tillämpas. Läs/skriv boolean .

**Returns:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


Avgör om smarttaggen ska rensas. Inget arv tillämpas. Läs/skriv boolean .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


Returnerar eller sätter hyperlänken som definierats för musklick. Läs/skriv [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


Returnerar eller sätter hyperlänken som definierats för musklick. Läs/skriv [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


Returnerar eller sätter hyperlänken som definierats för mus över. Läs/skriv [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


Returnerar eller sätter hyperlänken som definierats för mus över. Läs/skriv [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


Hyperlänkhanteerare. Endast läs [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Returns:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```


Hämtar effektiva formateringsdata för delen med arv tillämpat.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).