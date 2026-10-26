---
title: IParagraph
second_title: Aspose.Slides dla Java – Referencja API
description: Reprezentuje akapit tekstu.
type: docs
url: /pl/com.aspose.slides/iparagraph/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Represents a paragraph of a text.
## Metody

| Metoda | Opis |
| --- | --- |
| [getPortions()](#getPortions--) | Zwraca kolekcję fragmentów tekstu. |
| [getParagraphFormat()](#getParagraphFormat--) | Zwraca obiekt formatowania tego akapitu. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy segmenty o tym samym formatowaniu. |
| [getText()](#getText--) | Pobiera lub ustawia zwykły tekst akapitu. |
| [setText(String value)](#setText-java.lang.String-) | Pobiera lub ustawia zwykły tekst akapitu. |
| [getRect()](#getRect--) | Pobiera współrzędne prostokąta, który otacza akapit. |
| [getLinesCount()](#getLinesCount--) | Pobiera liczbę wierszy w akapicie. |
| [getImage()](#getImage--) | Zwraca obraz akapitu. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Zwraca obraz akapitu w określonej skali. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Określa właściwości fragmentu, które mają być użyte, jeśli po ostatnim zostanie wstawiony kolejny fragment. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Określa właściwości fragmentu, które mają być użyte, jeśli po ostatnim zostanie wstawiony kolejny fragment. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Zwraca kolekcję fragmentów tekstu. Tylko do odczytu [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Zwraca:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


Zwraca obiekt formatowania tego akapitu. Tylko do odczytu [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Zwraca:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Łączy segmenty o tym samym formatowaniu.

### getText() {#getText--}
```
public abstract String getText()
```


Pobiera lub ustawia zwykły tekst akapitu. Odczyt/zapis String.

Wartość: Tekst.

**Zwraca:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Pobiera lub ustawia zwykły tekst akapitu. Odczyt/zapis String.

Wartość: Tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


Pobiera współrzędne prostokąta, który otacza akapit. Prostokąt obejmuje wszystkie wiersze tekstu w akapicie, w tym puste.

**Zwraca:**
java.awt.geom.Rectangle2D.Float - Prostokąt, który otacza akapit java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```


Pobiera liczbę wierszy w akapicie.

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

**Zwraca:**
int - liczba wierszy w akapicie
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Zwraca obraz akapitu.

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

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Obraz zawierający wyrenderowany akapit, lub null jeśli akapit nie może zostać znaleziony w kolekcji nadrzędnej, nie ma prawidłowych granic renderowania lub wystąpi błąd podczas renderowania obrazu.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```


Zwraca obraz akapitu w określonej skali.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| scaleX | float | Poziomy współczynnik skali stosowany do obrazu akapitu. |
| scaleY | float | Pionowy współczynnik skali stosowany do obrazu akapitu. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Obraz zawierający wyrenderowany akapit, lub null jeśli akapit nie może zostać znaleziony w kolekcji nadrzędnej, nie ma prawidłowych granic renderowania lub wystąpi błąd podczas renderowania obrazu.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Określa właściwości fragmentu, które mają być użyte, jeśli po ostatnim zostanie wstawiony kolejny fragment.

**Zwraca:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Określa właściwości fragmentu, które mają być użyte, jeśli po ostatnim zostanie wstawiony kolejny fragment.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |