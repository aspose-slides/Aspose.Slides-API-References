---
title: IParagraph
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Reprezentuje odstavec textu.
type: docs
url: /cs/com.aspose.slides/iparagraph/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Reprezentuje odstavec textu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getPortions()](#getPortions--) | Vrací kolekci částí textu. |
| [getParagraphFormat()](#getParagraphFormat--) | Vrací objekt formátování pro tento odstavec. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojí úseky se stejným formátováním. |
| [getText()](#getText--) | Získává nebo nastavuje prostý text odstavce. |
| [setText(String value)](#setText-java.lang.String-) | Získává nebo nastavuje prostý text odstavce. |
| [getRect()](#getRect--) | Získá souřadnice obdélníku ohraničujícího odstavec. |
| [getLinesCount()](#getLinesCount--) | Získá počet řádků v odstavci. |
| [getImage()](#getImage--) | Vrací obrázek odstavce. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Vrací obrázek odstavce se zadaným měřítkem. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Určuje vlastnosti úseku, které se mají použít, pokud je po posledním úseku vložen další. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Určuje vlastnosti úseku, které se mají použít, pokud je po posledním úseku vložen další. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Vrací kolekci částí textu. Pouze pro čtení [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Vrací:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


Vrací objekt formátování pro tento odstavec. Pouze pro čtení [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Vrací:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Spojí úseky se stejným formátováním.

### getText() {#getText--}
```
public abstract String getText()
```


Získává nebo nastavuje prostý text odstavce. Čtení/Zápis String.

Hodnota: Text.

**Vrací:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Získává nebo nastavuje prostý text odstavce. Čtení/Zápis String.

Hodnota: Text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


Získá souřadnice obdélníku ohraničujícího odstavec. Obdélník zahrnuje všechny řádky textu v odstavci, včetně prázdných.

**Vrací:**
java.awt.geom.Rectangle2D.Float - Rectangle that bounds paragraph java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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

**Vrací:**
int - Počet řádků v odstavci
### getImage() {#getImage--}
```
public abstract IImage getImage()
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

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Obrázek obsahující vykreslený odstavec, nebo null, pokud odstavec nelze najít v nadřazené kolekci, nemá platné hranice pro vykreslení, nebo dojde k chybě při vykreslování obrázku.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
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
| scaleX | float | Horizontální faktor měřítka aplikovaný na obrázek odstavce. |
| scaleY | float | Vertikální faktor měřítka aplikovaný na obrázek odstavce. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Obrázek obsahující vykreslený odstavec, nebo null, pokud odstavec nelze najít v nadřazené kolekci, nemá platné hranice pro vykreslení, nebo dojde k chybě při vykreslování obrázku.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Určuje vlastnosti úseku, které se mají použít, pokud je po posledním úseku vložen další.

**Vrací:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Určuje vlastnosti úseku, které se mají použít, pokud je po posledním úseku vložen další.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |