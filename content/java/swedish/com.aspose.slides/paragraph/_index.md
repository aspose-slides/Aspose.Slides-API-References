---
title: Paragraph
second_title: Aspose.Slides för Java API-referens
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
| [Paragraph()](#Paragraph--) | Initialiserar en ny instans av klassen Paragraph med standardegenskaper. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Kopieringskonstruktor som initierar en ny instans av en Paragraph-klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPortions()](#getPortions--) | Returnerar samlingen av textdelar. |
| [getParagraphFormat()](#getParagraphFormat--) | Returnerar formateringsobjektet för detta stycke. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Sammanfogar körningar med samma formatering. |
| [getText()](#getText--) | Hämtar eller anger den enkla texten i ett stycke. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger den enkla texten i ett stycke. |
| [getRect()](#getRect--) | Hämtar koordinaterna för rektangeln som omsluter stycket. |
| [getLinesCount()](#getLinesCount--) | Hämtar antalet rader i ett stycke. |
| [getImage()](#getImage--) | Returnerar en bild av stycket. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Returnerar en bild av stycket med angiven skala. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Anger de egenskaper för delen som ska användas om en annan del infogas efter den sista. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Anger de egenskaper för delen som ska användas om en annan del infogas efter den sista. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för ett stycke. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för ett stycke. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Initialiserar en ny instans av Paragraph-klassen med standardegenskaper.

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

Returnerar samlingen av textdelar. Skrivskyddad [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Returnerar:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Returnerar formateringsobjektet för detta stycke. Skrivskyddad [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Formateringsobjektet innehåller de formateringsparametrar som enbart är definierade för det aktuella stycket, ärvd data tillämpas inte.

För att få de effektiva värdena inklusive ärvda, använd metoden [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Returnerar:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Sammanfogar körningar med samma formatering.

### getText() {#getText--}
```
public final String getText()
```

Hämtar eller anger den enkla texten i ett stycke. Läs/skriv Sträng.

Värde: Texten.

**Returnerar:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Hämtar eller anger den enkla texten i ett stycke. Läs/skriv Sträng.

Värde: Texten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Hämtar koordinaterna för rektangeln som omsluter stycket. Rektangeln innehåller alla rader i stycket, inklusive tomma.

**Returnerar:**
java.awt.geom.Rectangle2D.Float
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
### getImage() {#getImage--}
```
public final IImage getImage()
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
[IImage](../../com.aspose.slides/iimage) - En bild som innehåller det renderade stycket, eller null om stycket inte kan hittas i sin föräldrakollektion, har inga giltiga renderingsgränser, eller ett fel uppstår under rendering av bilden.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
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
[IImage](../../com.aspose.slides/iimage) - En bild som innehåller det renderade stycket, eller null om stycket inte kan hittas i sin föräldrakollektion, har inga giltiga renderingsgränser, eller ett fel uppstår under rendering av bilden.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Anger de egenskaper för delen som ska användas om en annan del infogas efter den sista.

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Anger de egenskaper för delen som ska användas om en annan del infogas efter den sista.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den överordnade bilden för ett stycke. Skrivskyddad [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för ett stycke. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)