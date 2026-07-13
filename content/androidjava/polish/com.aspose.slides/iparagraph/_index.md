---
title: IParagraph
second_title: Aspose.Slides dla Androida – referencja API Java
description: Reprezentuje akapit tekstu.
type: docs
url: /pl/com.aspose.slides/iparagraph/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Reprezentuje akapit tekstu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getPortions()](#getPortions--) | Zwraca kolekcję fragmentów tekstu. |
| [getParagraphFormat()](#getParagraphFormat--) | Zwraca obiekt formatowania dla tego akapitu. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy fragmenty o tym samym formatowaniu. |
| [getText()](#getText--) | Pobiera lub ustawia zwykły tekst akapitu. |
| [setText(String value)](#setText-java.lang.String-) | Pobiera lub ustawia zwykły tekst akapitu. |
| [getRect()](#getRect--) | Pobiera współrzędne prostokąta otaczającego akapit. |
| [getLinesCount()](#getLinesCount--) | Pobiera liczbę wierszy w akapicie. |
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

Zwraca obiekt formatowania dla tego akapitu. Tylko do odczytu [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Zwraca:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Łączy fragmenty o tym samym formatowaniu.

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
public abstract RectF getRect()
```

Pobiera współrzędne prostokąta otaczającego akapit. Prostokąt obejmuje wszystkie linie tekstu w akapicie, w tym puste.

**Zwraca:**
android.graphics.RectF - Prostokąt otaczający akapit android.graphics.RectF
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
int - Liczba wierszy w akapicie
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