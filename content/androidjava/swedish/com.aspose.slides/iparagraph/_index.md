---
title: IParagraph
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett stycke av en text.
type: docs
url: /sv/com.aspose.slides/iparagraph/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Representerar ett stycke i en text.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPortions()](#getPortions--) | Returnerar samlingen av textdelar. |
| [getParagraphFormat()](#getParagraphFormat--) | Returnerar formateringsobjektet för detta stycke. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Sammanfogar körningar med samma formatering. |
| [getText()](#getText--) | Hämtar eller anger den rena texten i ett stycke. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger den rena texten i ett stycke. |
| [getRect()](#getRect--) | Hämtar koordinaterna för rektangeln som omsluter stycket. |
| [getLinesCount()](#getLinesCount--) | Hämtar antalet rader i ett stycke. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Anger delens egenskaper som ska användas om en annan del infogas efter den sista. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Anger delens egenskaper som ska användas om en annan del infogas efter den sista. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Returnerar samlingen av textdelar. Skrivskyddad [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Returnerar:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Returnerar formateringsobjektet för detta stycke. Skrivskyddad [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returnerar:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Sammanfogar körningar med samma formatering.

### getText() {#getText--}
```
public abstract String getText()
```

Hämtar eller anger den rena texten i ett stycke. Läs/skriv String.

Value: The text.

**Returnerar:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Hämtar eller anger den rena texten i ett stycke. Läs/skriv String.

Value: The text.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Hämtar koordinaterna för rektangeln som omsluter stycket. Rektangeln inkluderar alla textrader i stycket, inklusive tomma.

**Returnerar:**
android.graphics.RectF - Rectangle that bounds paragraph android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Anger delens egenskaper som ska användas om en annan del infogas efter den sista.

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

Anger delens egenskaper som ska användas om en annan del infogas efter den sista.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |