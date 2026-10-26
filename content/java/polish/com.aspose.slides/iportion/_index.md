---
title: IPortion
second_title: Aspose.Slides dla Java - Dokumentacja API
description: Reprezentuje fragment tekstu w akapicie tekstowym.
type: docs
url: /pl/com.aspose.slides/iportion/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Reprezentuje fragment tekstu wewnątrz akapitu tekstowego.
## Metody

| Metoda | Opis |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Zwraca obiekt formatowania, który zawiera jawnie ustawione właściwości formatowania fragmentu tekstu bez zastosowania dziedziczenia. |
| [getText()](#getText--) | Pobiera lub ustawia zwykły tekst fragmentu. |
| [setText(String value)](#setText-java.lang.String-) | Pobiera lub ustawia zwykły tekst fragmentu. |
| [getField()](#getField--) | Zwraca pole tego fragmentu. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Konwertuje ten fragment na automatycznie aktualizowane pole. |
| [addField(String internalString)](#addField-java.lang.String-) | Konwertuje ten fragment na automatycznie aktualizowane pole. |
| [removeField()](#removeField--) | Konwertuje ten fragment pola na prosty fragment. |
| [getRect()](#getRect--) | Pobiera współrzędne prostokąta ograniczającego fragment. |
| [getCoordinates()](#getCoordinates--) | Pobiera współrzędne początku fragmentu. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Zwraca obiekt formatowania, który zawiera jawnie ustawione właściwości formatowania fragmentu tekstu bez zastosowania dziedziczenia. Tylko do odczytu [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Obiekt formatowania zawiera jedynie parametry formatowania zdefiniowane dla bieżącego fragmentu, dane odziedziczone nie są stosowane.

Aby uzyskać wartości efektywne, w tym odziedziczone, użyj metody [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Zwraca:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Pobiera lub ustawia zwykły tekst fragmentu. Odczyt/zapis String.

Wartość: Tekst.

**Zwraca:**  
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Pobiera lub ustawia zwykły tekst fragmentu. Odczyt/zapis String.

Wartość: Tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```

Zwraca pole tego fragmentu. Tylko do odczytu [IField](../../com.aspose.slides/ifield).

**Zwraca:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

Konwertuje ten fragment na automatycznie aktualizowane pole.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Typ pola [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

Konwertuje ten fragment na automatycznie aktualizowane pole.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| internalString | java.lang.String | Wewnętrzna nazwa ciągu FieldTypeEx |
### removeField() {#removeField--}
```
public abstract void removeField()
```

Konwertuje ten fragment pola na prosty fragment.
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Pobiera współrzędne prostokąta ograniczającego fragment. Prostokąt obejmuje wszystkie linie tekstu w fragmencie, w tym puste.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**  
java.awt.geom.Rectangle2D.Float - Prostokąt ograniczający fragment java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```

Pobiera współrzędne początku fragmentu. Współrzędna X punktu reprezentuje początek fragmentu od pierwszego znaku, włączając lewy odstęp. Współrzędna Y obejmuje górny odstęp.

**Zwraca:**  
java.awt.geom.Point2D.Float - Współrzędne początku fragmentu java.awt.geom.Point2D.Float