---
title: IParagraph
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een alinea van een tekst voor.
type: docs
url: /nl/com.aspose.slides/iparagraph/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Stelt een alinea van een tekst voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPortions()](#getPortions--) | Retourneert de collectie van tekstonderdelen. |
| [getParagraphFormat()](#getParagraphFormat--) | Retourneert het opmaakobject voor deze alinea. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs samen met dezelfde opmaak. |
| [getText()](#getText--) | Haalt op of stelt de platte tekst van een alinea in. |
| [setText(String value)](#setText-java.lang.String-) | Haalt op of stelt de platte tekst van een alinea in. |
| [getRect()](#getRect--) | Haalt de coördinaten op van de rechthoek die de alinea begrenst. |
| [getLinesCount()](#getLinesCount--) | Haalt het aantal regels in een alinea op. |
| [getImage()](#getImage--) | Retourneert een afbeelding van de alinea. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Retourneert een afbeelding van de alinea met de opgegeven schaal. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Specificeert de gedeelte-eigenschappen die moeten worden gebruikt als een ander gedeelte wordt ingevoegd na het laatste. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Specificeert de gedeelte-eigenschappen die moeten worden gebruikt als een ander gedeelte wordt ingevoegd na het laatste. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Retourneert de collectie van tekstonderdelen. Alleen-lezen [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Retour:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Retourneert het opmaakobject voor deze alinea. Alleen-lezen [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retour:**
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

Haalt op of stelt de platte tekst van een alinea in. Lezen/Schrijven String.

Waarde: De tekst.

**Retour:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Haalt op of stelt de platte tekst van een alinea in. Lezen/Schrijven String.

Waarde: De tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Haalt de coördinaten op van de rechthoek die de alinea begrenst. De rechthoek omvat alle tekstregels in de alinea, inclusief lege regels.

**Retour:**
java.awt.geom.Rectangle2D.Float - Rectangle that bounds paragraph java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

Haalt het aantal regels in een alinea op.

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

**Retour:**
int - Aantal regels in een alinea
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Retourneert een afbeelding van de alinea.

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

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Een afbeelding die de gerenderde alinea bevat, of null als de alinea niet kan worden gevonden in de bovenliggende collectie, geen geldige renderingsbounds heeft, of er een fout optreedt tijdens het renderen van de afbeelding.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Retourneert een afbeelding van de alinea met de opgegeven schaal.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | float | De horizontale schaalfactor die op de alinea-afbeelding wordt toegepast. |
| scaleY | float | De verticale schaalfactor die op de alinea-afbeelding wordt toegepast. |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Een afbeelding die de gerenderde alinea bevat, of null als de alinea niet kan worden gevonden in de bovenliggende collectie, geen geldige renderingsbounds heeft, of er een fout optreedt tijdens het renderen van de afbeelding.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Specificeert de gedeelte-eigenschappen die moeten worden gebruikt als een ander gedeelte wordt ingevoegd na het laatste.

**Retour:**
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