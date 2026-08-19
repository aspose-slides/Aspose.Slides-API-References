---
title: Paragraph
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een alinea met tekst voor.
type: docs
url: /nl/com.aspose.slides/paragraph/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Stelt een alinea met tekst voor.
## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [Paragraph()](#Paragraph--) | Initialiseert een nieuw exemplaar van de Paragraph klasse met standaard eigenschappen. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Kopie-constructor die een nieuw exemplaar van een Paragraph klasse initialiseert. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPortions()](#getPortions--) | Retourneert de collectie van tekstgedeelten. |
| [getParagraphFormat()](#getParagraphFormat--) | Retourneert het opmaakobject voor deze alinea. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs samen met dezelfde opmaak. |
| [getText()](#getText--) | Haalt of stelt de platte tekst van een alinea in. |
| [setText(String value)](#setText-java.lang.String-) | Haalt of stelt de platte tekst van een alinea in. |
| [getRect()](#getRect--) | Haal coördinaten van het rechthoekige gebied op dat de alinea begrenst. |
| [getLinesCount()](#getLinesCount--) | Haal het aantal regels in een alinea op. |
| [getImage()](#getImage--) | Retourneert een afbeelding van de alinea. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Retourneert een afbeelding van de alinea met de opgegeven schaal. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Specificeert de deel-eigenschappen die moeten worden gebruikt als een ander deel na het laatste wordt ingevoegd. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Specificeert de deel-eigenschappen die moeten worden gebruikt als een ander deel na het laatste wordt ingevoegd. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een alinea. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een alinea. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


Initialiseert een nieuw exemplaar van de Paragraph klasse met standaard eigenschappen.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


Kopie-constructor die een nieuw exemplaar van een Paragraph klasse initialiseert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```


Retourneert de collectie van tekstgedeelten. Alleen-lezen [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Retourneert:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```


Retourneert het opmaakobject voor deze alinea. Alleen-lezen [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Het opmaakobject bevat de opmaakparameters die alleen voor de huidige alinea zijn gedefinieerd; geërfde gegevens worden niet toegepast.

Om de effectieve waarden inclusief geërfde waarden te verkrijgen, gebruik de [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) methode.

**Retourneert:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Voegt runs samen met dezelfde opmaak.

### getText() {#getText--}
```
public final String getText()
```


Haalt of stelt de platte tekst van een alinea in. Lezen/Schrijven String.

Waarde: De tekst.

**Retourneert:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Haalt of stelt de platte tekst van een alinea in. Lezen/Schrijven String.

Waarde: De tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```


Haal coördinaten van het rechthoekige gebied op dat de alinea begrenst. Het gebied omvat alle tekstregels in de alinea, inclusief lege regels.

**Retourneert:**
java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
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
### getImage() {#getImage--}
```
public final IImage getImage()
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

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Een afbeelding die de gerenderde alinea bevat, of null als de alinea niet kan worden gevonden in de bovenliggende collectie, geen geldige renderingsgrenzen heeft, of er een fout optreedt tijdens het renderen van de afbeelding.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
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

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Een afbeelding die de gerenderde alinea bevat, of null als de alinea niet kan worden gevonden in de bovenliggende collectie, geen geldige renderingsgrenzen heeft, of er een fout optreedt tijdens het renderen van de afbeelding.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Specificeert de deel-eigenschappen die moeten worden gebruikt als een ander deel na het laatste wordt ingevoegd.

**Retourneert:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Specificeert de deel-eigenschappen die moeten worden gebruikt als een ander deel na het laatste wordt ingevoegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Retourneert de bovenliggende dia van een alinea. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Retourneert de bovenliggende presentatie van een alinea. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)