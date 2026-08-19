---
title: IParagraph
second_title: Aspose.Slides för Java API-referens
description: Representerar ett stycke av en text.
type: docs
url: /sv/com.aspose.slides/iparagraph/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Representerar ett stycke av en text.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPortions()](#getPortions--) | Returnerar samlingen av textdelar. |
| [getParagraphFormat()](#getParagraphFormat--) | Returnerar formateringsobjektet för detta stycke. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Sammanfogar körningar med samma formatering. |
| [getText()](#getText--) | Hämtar eller anger den rena texten för ett stycke. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger den rena texten för ett stycke. |
| [getRect()](#getRect--) | Hämtar koordinaterna för den rektangel som omger stycket. |
| [getLinesCount()](#getLinesCount--) | Hämtar antalet rader i ett stycke. |
| [getImage()](#getImage--) | Returnerar en bild av stycket. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Returnerar en bild av stycket med angiven skala. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Anger delens egenskaper som ska användas om en annan del infogas efter den sista. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Anger delens egenskaper som ska användas om en annan del infogas efter den sista. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Returnerar samlingen av textdelar. Endast läsning [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Returnerar:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Returnerar formateringsobjektet för detta stycke. Endast läsning [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

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

Hämtar eller anger den rena texten för ett stycke. Läs/skriv String.

Värde: Texten.

**Returnerar:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Hämtar eller anger den rena texten för ett stycke. Läs/skriv String.

Värde: Texten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Hämtar koordinaterna för den rektangel som omger stycket. Rektangeln inkluderar alla rader av text i stycket, inklusive tomma.

**Returnerar:**
java.awt.geom.Rectangle2D.Float - Rektangel som omger stycket java.awt.geom.Rectangle2D.Float
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
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Returnerar en bild av stycket.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - En bild som innehåller det renderade stycket, eller null om stycket inte kan hittas i sin föräldrakollektion, saknar giltiga renderingsgränser, eller om ett fel uppstår vid rendering av bilden.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Returnerar en bild av stycket med angiven skala.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | float | Den horisontella skalningsfaktorn som tillämpas på styckets bild. |
| scaleY | float | Den vertikala skalningsfaktorn som tillämpas på styckets bild. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - En bild som innehåller det renderade stycket, eller null om stycket inte kan hittas i sin föräldrakollektion, saknar giltiga renderingsgränser, eller om ett fel uppstår vid rendering av bilden.
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