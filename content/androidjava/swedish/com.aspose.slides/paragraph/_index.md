---
title: Paragraph
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett stycke text.
type: docs
url: /sv/com.aspose.slides/paragraph/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Representerar ett stycke text.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [Paragraph()](#Paragraph--) | Initierar en ny instans av Paragraph-klass med standardegenskaper. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Kopieringskonstruktor som initierar en ny instans av en Paragraph-klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPortions()](#getPortions--) | Returnerar samlingen av en textdelar. |
| [getParagraphFormat()](#getParagraphFormat--) | Returnerar formateringsobjektet för detta stycke. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Slår ihop körningar med samma formatering. |
| [getText()](#getText--) | Hämtar eller anger den vanliga texten i ett stycke. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger den vanliga texten i ett stycke. |
| [getRect()](#getRect--) | Hämtar koordinaterna för rektangeln som omger stycket. |
| [getLinesCount()](#getLinesCount--) | Hämtar antalet rader i ett stycke. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Anger delens egenskaper som ska användas om en annan del infogas efter den sista. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Anger delens egenskaper som ska användas om en annan del infogas efter den sista. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Returnerar föräldrasliden för ett stycke. |
| [getPresentation()](#getPresentation--) | Returnerar föräldrapresentationen för ett stycke. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


Initierar en ny instans av Paragraph-klass med standardegenskaper.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


Kopieringskonstruktor som initierar en ny instans av en Paragraph-klass.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```


Returnerar samlingen av en textdelar. Skrivskyddad [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Returnerar:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```


Returnerar formateringsobjektet för detta stycke. Skrivskyddad [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Formateringsobjektet innehåller de formateringsparametrar som är definierade endast för det aktuella stycket; ärvda data tillämpas inte.

För att få de effektiva värdena inklusive ärvda använder du metoden [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Returnerar:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Slår ihop körningar med samma formatering.

### getText() {#getText--}
```
public final String getText()
```


Hämtar eller anger den vanliga texten i ett stycke. Läs/skriv String.

Värde: Texten.

**Returnerar:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Hämtar eller anger den vanliga texten i ett stycke. Läs/skriv String.

Värde: Texten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```


Hämtar koordinaterna för rektangeln som omger stycket. Rektangeln inkluderar alla textrader i stycket, inklusive tomma.

**Returnerar:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```


Hämtar antalet rader i ett stycke.

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

**Returnerar:**
int - Antal rader i ett stycke
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Anger delens egenskaper som ska användas om en annan del infogas efter den sista.

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Anger delens egenskaper som ska användas om en annan del infogas efter den sista.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returnerar föräldrasliden för ett stycke. Skrivskyddad [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returnerar föräldrapresentationen för ett stycke. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)