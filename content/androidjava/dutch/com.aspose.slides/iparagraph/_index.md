---
title: IParagraph
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een alinea van tekst.
type: docs
url: /nl/com.aspose.slides/iparagraph/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Vertegenwoordigt een alinea van tekst.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPortions()](#getPortions--) | Geeft de collectie van tekstgedeelten terug. |
| [getParagraphFormat()](#getParagraphFormat--) | Geeft het opmaakobject voor deze alinea terug. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs samen met dezelfde opmaak. |
| [getText()](#getText--) | Haalt de platte tekst van een alinea op of stelt deze in. |
| [setText(String value)](#setText-java.lang.String-) | Haalt de platte tekst van een alinea op of stelt deze in. |
| [getRect()](#getRect--) | Haal de coördinaten op van de rechthoek die de alinea begrenst. |
| [getLinesCount()](#getLinesCount--) | Haal het aantal regels in een alinea op. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Specificeert de gedeelte-eigenschappen die moeten worden gebruikt als een ander gedeelte wordt ingevoegd na het laatste. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Specificeert de gedeelte-eigenschappen die moeten worden gebruikt als een ander gedeelte wordt ingevoegd na het laatste. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Geeft de collectie van tekstgedeelten terug. Alleen-lezen [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Retourneert:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


Geeft het opmaakobject voor deze alinea terug. Alleen-lezen [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retourneert:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Voegt runs samen met dezelfde opmaak.

### getText() {#getText--}
```
public abstract String getText()
```


Haalt de platte tekst van een alinea op of stelt deze in. Lezen/schrijven String.

Waarde: De tekst.

**Retourneert:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Haalt de platte tekst van een alinea op of stelt deze in. Lezen/schrijven String.

Waarde: De tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```


Haal de coördinaten op van de rechthoek die de alinea begrenst. De rechthoek omvat alle regels tekst in de alinea, inclusief lege regels.

**Retourneert:**
android.graphics.RectF - Rechthoek die de alinea begrenst android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```


Haal het aantal regels in een alinea op.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
int - Aantal regels in een alinea
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Specificeert de gedeelte-eigenschappen die moeten worden gebruikt als een ander gedeelte wordt ingevoegd na het laatste.

**Retourneert:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Specificeert de gedeelte-eigenschappen die moeten worden gebruikt als een ander gedeelte wordt ingevoegd na het laatste.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |