---
title: Paragraph
second_title: Aspose.Slides dla Androida za pomocą Java API Reference
description: Reprezentuje akapit tekstu.
type: docs
url: /pl/com.aspose.slides/paragraph/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Reprezentuje akapit tekstu.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [Paragraph()](#Paragraph--) | Inicjalizuje nową instancję klasy Paragraph z domyślnymi właściwościami. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Konstruktor kopiujący, który inicjalizuje nową instancję klasy Paragraph. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getPortions()](#getPortions--) | Zwraca kolekcję fragmentów tekstu. |
| [getParagraphFormat()](#getParagraphFormat--) | Zwraca obiekt formatowania dla tego akapitu. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy segmenty o tym samym formatowaniu. |
| [getText()](#getText--) | Pobiera lub ustawia zwykły tekst akapitu. |
| [setText(String value)](#setText-java.lang.String-) | Pobiera lub ustawia zwykły tekst akapitu. |
| [getRect()](#getRect--) | Pobiera współrzędne prostokąta obejmującego akapit. |
| [getLinesCount()](#getLinesCount--) | Pobiera liczbę wierszy w akapicie. |
| [getImage()](#getImage--) | Zwraca obraz akapitu. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Zwraca obraz akapitu w określonej skali. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Określa właściwości fragmentu, które mają być użyte, jeśli po ostatnim zostanie wstawiony kolejny fragment. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Określa właściwości fragmentu, które mają być użyte, jeśli po ostatnim zostanie wstawiony kolejny fragment. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny akapitu. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną akapitu. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Inicjalizuje nową instancję klasy Paragraph z domyślnymi właściwościami.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Konstruktor kopiujący, który inicjalizuje nową instancję klasy Paragraph.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Zwraca kolekcję fragmentów tekstu. Tylko do odczytu [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Zwraca:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Zwraca obiekt formatowania dla tego akapitu. Tylko do odczytu [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Obiekt formatowania zawiera jedynie parametry formatowania zdefiniowane dla bieżącego akapitu; dziedziczone dane nie są stosowane.

Aby uzyskać efektywne wartości, w tym dziedziczone, użyj metody [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Zwraca:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Łączy segmenty o tym samym formatowaniu.

### getText() {#getText--}
```
public final String getText()
```

Pobiera lub ustawia zwykły tekst akapitu. Odczyt/zapis String.

Wartość: Tekst.

**Zwraca:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Pobiera lub ustawia zwykły tekst akapitu. Odczyt/zapis String.

Wartość: Tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

Pobiera współrzędne prostokąta obejmującego akapit. Prostokąt zawiera wszystkie linie tekstu w akapicie, w tym puste.

**Zwraca:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
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
int - Liczba wierszy w akapicie
### getImage() {#getImage--}
```
public final IImage getImage()
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
[IImage](../../com.aspose.slides/iimage) - Obraz zawierający renderowany akapit, lub null jeśli akapit nie zostanie znaleziony w kolekcji nadrzędnej, nie ma prawidłowych granic renderowania lub wystąpi błąd podczas renderowania obrazu.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
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
| scaleX | float | Czynnik skali poziomej zastosowany do obrazu akapitu. |
| scaleY | float | Czynnik skali pionowej zastosowany do obrazu akapitu. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Obraz zawierający renderowany akapit, lub null jeśli akapit nie zostanie znaleziony w kolekcji nadrzędnej, nie ma prawidłowych granic renderowania lub wystąpi błąd podczas renderowania obrazu.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Określa właściwości fragmentu, które mają być użyte, jeśli po ostatnim zostanie wstawiony kolejny fragment.

**Zwraca:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Określa właściwości fragmentu, które mają być użyte, jeśli po ostatnim zostanie wstawiony kolejny fragment.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca nadrzędny slajd akapitu. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca nadrzędną prezentację akapitu. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)