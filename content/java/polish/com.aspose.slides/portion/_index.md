---
title: Portion
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje fragment tekstu w akapicie tekstowym.
type: docs
url: /pl/com.aspose.slides/portion/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Reprezentuje fragment tekstu wewnątrz akapitu tekstowego.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [Portion()](#Portion--) | Inicjalizuje nową instancję klasy Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Inicjalizuje nową instancję klasy Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Inicjalizuje nową instancję klasy Portion. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Zwraca obiekt formatowania, który zawiera wyraźnie ustawione właściwości formatowania fragmentu tekstu bez zastosowanego dziedziczenia. |
| [getText()](#getText--) | Pobiera lub ustawia zwykły tekst fragmentu. |
| [setText(String value)](#setText-java.lang.String-) | Pobiera lub ustawia zwykły tekst fragmentu. |
| [getField()](#getField--) | Zwraca pole tego fragmentu. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Konwertuje ten fragment na automatycznie aktualizowane pole. |
| [addField(String internalString)](#addField-java.lang.String-) | Konwertuje ten fragment na automatycznie aktualizowane pole. |
| [removeField()](#removeField--) | Konwertuje ten fragment pola na prosty fragment. |
| [getRect()](#getRect--) | Pobiera współrzędne prostokąta otaczającego fragment. |
| [getCoordinates()](#getCoordinates--) | Pobiera współrzędne początku fragmentu. |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny tekstu. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną tekstu. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Inicjalizuje nową instancję klasy Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Inicjalizuje nową instancję klasy Portion.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Inicjalizuje nową instancję klasy Portion.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Zwraca obiekt formatowania, który zawiera wyraźnie ustawione właściwości formatowania fragmentu tekstu bez zastosowanego dziedziczenia. Tylko do odczytu [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Obiekt formatowania zawiera jedynie parametry formatowania zdefiniowane dla bieżącego fragmentu, dziedziczone dane nie są stosowane.

Aby uzyskać efektywne wartości, w tym dziedziczone, użyj metody [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Zwraca:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Pobiera lub ustawia zwykły tekst fragmentu. Odczyt/zapis String.

Wartość: Tekst.

**Zwraca:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Pobiera lub ustawia zwykły tekst fragmentu. Odczyt/zapis String.

Wartość: Tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Zwraca pole tego fragmentu. Tylko do odczytu [IField](../../com.aspose.slides/ifield).

**Zwraca:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Konwertuje ten fragment na automatycznie aktualizowane pole.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Konwertuje ten fragment na automatycznie aktualizowane pole.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| internalString | java.lang.String | Wewnętrzna nazwa FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Konwertuje ten fragment pola na prosty fragment.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Pobiera współrzędne prostokąta otaczającego fragment. Prostokąt obejmuje wszystkie linie tekstu w fragmencie, włącznie z pustymi.

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
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(1).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

Pobiera współrzędne początku fragmentu. Współrzędna X punktu reprezentuje początek fragmentu od pierwszego znaku, łącznie z lewym marginesem. Współrzędna Y obejmuje górny margines.

**Zwraca:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca slajd nadrzędny tekstu. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację nadrzędną tekstu. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject