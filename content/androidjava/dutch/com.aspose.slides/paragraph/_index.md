---
title: Paragraph
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een alinea tekst voor.
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

Stelt een alinea tekst voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Paragraph()](#Paragraph--) | Initialiseert een nieuw exemplaar van de Paragraph klasse met standaard eigenschappen. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Kopieconstructor die een nieuw exemplaar van de Paragraph klasse initialiseert. |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getPortions()](#getPortions--) | Retourneert de verzameling van tekstporties. |
| [getParagraphFormat()](#getParagraphFormat--) | Retourneert het opmaakobject voor deze alinea. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs samen met dezelfde opmaak. |
| [getText()](#getText--) | Haalt op of stelt de platte tekst van een alinea in. |
| [setText(String value)](#setText-java.lang.String-) | Haalt op of stelt de platte tekst van een alinea in. |
| [getRect()](#getRect--) | Haal de coördinaten op van het rechthoek dat de alinea omsluit. |
| [getLinesCount()](#getLinesCount--) | Haal het aantal regels in een alinea op. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Specificeert de portie-eigenschappen die gebruikt moeten worden als een andere portie na de laatste wordt ingevoegd. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Specificeert de portie-eigenschappen die gebruikt moeten worden als een andere portie na de laatste wordt ingevoegd. |
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

Kopieconstructor die een nieuw exemplaar van de Paragraph klasse initialiseert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |
### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Retourneert de verzameling van tekstporties. Alleen-lezen [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Retour:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Retourneert het opmaakobject voor deze alinea. Alleen-lezen [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Het opmaakobject bevat alleen de opmaakparameters die voor de huidige alinea zijn gedefinieerd; geërfde gegevens worden niet toegepast.

Om de effectieve waarden, inclusief geërfde, te verkrijgen, gebruik de [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) methode.

**Retour:**
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

Haalt op of stelt de platte tekst van een alinea in. Lezen/schrijven String.

Waarde: De tekst.

**Retour:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Haalt op of stelt de platte tekst van een alinea in. Lezen/schrijven String.

Waarde: De tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public final RectF getRect()
```

Haal de coördinaten op van het rechthoek dat de alinea omsluit. Het rechthoek omvat alle tekstregels in de alinea, inclusief lege.

**Retour:**
android.graphics.RectF
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

**Retour:**
int - Aantal regels in een alinea
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Specificeert de portie-eigenschappen die gebruikt moeten worden als een andere portie na de laatste wordt ingevoegd.

**Retour:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Specificeert de portie-eigenschappen die gebruikt moeten worden als een andere portie na de laatste wordt ingevoegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende dia van een alinea. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retour:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een alinea. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation)