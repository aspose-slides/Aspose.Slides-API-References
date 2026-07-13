---
title: Paragraph
second_title: Aspose.Slides dla Androida – odwołanie do API Java
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
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy ciągi o tym samym formatowaniu. |
| [getText()](#getText--) | Pobiera lub ustawia zwykły tekst akapitu. |
| [setText(String value)](#setText-java.lang.String-) | Pobiera lub ustawia zwykły tekst akapitu. |
| [getRect()](#getRect--) | Pobiera współrzędne prostokąta otaczającego akapit. |
| [getLinesCount()](#getLinesCount--) | Pobiera liczbę wierszy w akapicie. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Określa właściwości części, które mają być użyte, jeśli po ostatniej zostanie wstawiona kolejna część. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Określa właściwości części, które mają być użyte, jeśli po ostatniej zostanie wstawiona kolejna część. |
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

Obiekt formatowania zawiera parametry formatowania zdefiniowane wyłącznie dla bieżącego akapitu, dziedziczone dane nie są stosowane.

Aby uzyskać skuteczne wartości, w tym dziedziczone, użyj metody [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Zwraca:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Łączy ciągi o tym samym formatowaniu.

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


Pobiera współrzędne prostokąta otaczającego akapit. Prostokąt obejmuje wszystkie linie tekstu w akapicie, w tym puste.

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
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Określa właściwości części, które mają być użyte, jeśli po ostatniej zostanie wstawiona kolejna część.

**Zwraca:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Określa właściwości części, które mają być użyte, jeśli po ostatniej zostanie wstawiona kolejna część.

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


Zwraca slajd nadrzędny akapitu. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Zwraca prezentację nadrzędną akapitu. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)