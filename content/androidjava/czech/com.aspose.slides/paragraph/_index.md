---
title: Paragraph
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje odstavec textu.
type: docs
url: /cs/com.aspose.slides/paragraph/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Představuje odstavec textu.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Paragraph()](#Paragraph--) | Inicializuje novou instanci třídy Paragraph s výchozími vlastnostmi. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Kopírovací konstruktor, který inicializuje novou instanci třídy Paragraph. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getPortions()](#getPortions--) | Vrací kolekci textových částí. |
| [getParagraphFormat()](#getParagraphFormat--) | Vrací objekt formátování pro tento odstavec. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojuje úseky se stejným formátováním. |
| [getText()](#getText--) | Získá nebo nastaví prostý text odstavce. |
| [setText(String value)](#setText-java.lang.String-) | Získá nebo nastaví prostý text odstavce. |
| [getRect()](#getRect--) | Získá souřadnice obdélníku ohraničujícího odstavec. |
| [getLinesCount()](#getLinesCount--) | Získá počet řádků v odstavci. |
| [getImage()](#getImage--) | Vrací obrázek odstavce. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Vrací obrázek odstavce se zadaným měřítkem. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Určuje vlastnosti části, které se mají použít, pokud je po poslední vložena další část. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Určuje vlastnosti části, které se mají použít, pokud je po poslední vložena další část. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek odstavce. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci odstavce. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Inicializuje novou instanci třídy Paragraph s výchozími vlastnostmi.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Kopírovací konstruktor, který inicializuje novou instanci třídy Paragraph.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Vrací kolekci textových částí. Pouze ke čtení [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Návratová hodnota:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Vrací objekt formátování pro tento odstavec. Pouze ke čtení [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Objekt formátování obsahuje parametry formátování definované pouze pro aktuální odstavec, zděděná data se nepoužívají.

Pro získání efektivních hodnot včetně zděděných použijte metodu [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Návratová hodnota:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Spojuje úseky se stejným formátováním.

### getText() {#getText--}
```
public final String getText()
```

Získá nebo nastaví prostý text odstavce. Čtení/Zápis String.

Hodnota: Text.

**Návratová hodnota:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Získá nebo nastaví prostý text odstavce. Čtení/Zápis String.

Hodnota: Text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

Získá souřadnice obdélníku ohraničujícího odstavec. Obdélník zahrnuje všechny řádky textu v odstavci, včetně prázdných.

**Návratová hodnota:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

Získá počet řádků v odstavci.

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

**Návratová hodnota:**
int – Počet řádků v odstavci
### getImage() {#getImage--}
```
public final IImage getImage()
```

Vrací obrázek odstavce.

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

**Návratová hodnota:**
[IImage](../../com.aspose.slides/iimage) – Obrázek obsahující vykreslený odstavec, nebo null, pokud odstavec nelze najít v jeho nadřazené kolekci, nemá platné vykreslovací hranice, nebo dojde k chybě při vykreslování obrázku.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Vrací obrázek odstavce se zadaným měřítkem.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| scaleX | float | Horizontální měřítkový faktor aplikovaný na obrázek odstavce. |
| scaleY | float | Vertikální měřítkový faktor aplikovaný na obrázek odstavce. |

**Návratová hodnota:**
[IImage](../../com.aspose.slides/iimage) – Obrázek obsahující vykreslený odstavec, nebo null, pokud odstavec nelze najít v jeho nadřazené kolekci, nemá platné vykreslovací hranice, nebo dojde k chybě při vykreslování obrázku.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Určuje vlastnosti části, které se mají použít, pokud je po poslední vložena další část.

**Návratová hodnota:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Určuje vlastnosti části, které se mají použít, pokud je po poslední vložena další část.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Návratová hodnota:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek odstavce. Pouze ke čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Návratová hodnota:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci odstavce. Pouze ke čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation)