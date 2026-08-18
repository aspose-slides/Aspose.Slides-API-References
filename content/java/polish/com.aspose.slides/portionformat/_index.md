---
title: PortionFormat
second_title: Aspose.Slides dla Java - odniesienie API
description: Ta klasa zawiera właściwości formatowania części tekstu.
type: docs
url: /pl/com.aspose.slides/portionformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Ta klasa zawiera właściwości formatowania części tekstu. W przeciwieństwie do [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Utwórz obiekt prezentacji reprezentujący plik prezentacji
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides używa tych specjalnych identyfikatorów (podobnych do tych używanych w PowerPoint):
>      // +mn-lt - Czcionka ciała Latin (Mniejsza czcionka Latin)
>      // +mj-lt -Czcionka nagłówka Latin (Główna czcionka Latin)
>      // +mn-ea - Czcionka ciała East Asian (Mniejsza czcionka East Asian)
>      // +mj-ea - Czcionka ciała East Asian (Mniejsza czcionka East Asian)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Ta klasa jest używana do zwracania i manipulowania właściwościami formatowania części tekstu zdefiniowanymi dla konkretnej części. Oznacza to, że nie zastosowano dziedziczenia przy pobieraniu wartości, więc w większości przypadków otrzymasz wartości oznaczające "undefined".

Aby uzyskać skuteczne wartości parametrów formatowania, w tym dziedziczone, należy użyć metody [getEffective](../../com.aspose.slides/portionformat\#getEffective), która zwraca instancję [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Inicjalizuje nową instancję klasy [PortionFormat](../../com.aspose.slides/portionformat). |

## Metody

| Metoda | Opis |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Zwraca lub ustawia identyfikator zakładki. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Zwraca lub ustawia identyfikator zakładki. |
| [getSmartTagClean()](#getSmartTagClean--) | Określa, czy smart tag powinien być wyczyszczony. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Określa, czy smart tag powinien być wyczyszczony. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Zwraca lub ustawia hiperlink zdefiniowany dla kliknięcia myszy. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Zwraca lub ustawia hiperlink zdefiniowany dla kliknięcia myszy. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Zwraca lub ustawia hiperlink zdefiniowany przy najechaniu myszą. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Zwraca lub ustawia hiperlink zdefiniowany przy najechaniu myszą. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Menedżer hiperłączy. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane formatowania części z zastosowanym dziedziczeniem. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

Inicjalizuje nową instancję klasy [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

Zwraca lub ustawia identyfikator zakładki. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

Zwraca lub ustawia identyfikator zakładki. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

Określa, czy smart tag powinien być wyczyszczony. Nie zastosowano dziedziczenia. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

Określa, czy smart tag powinien być wyczyszczony. Nie zastosowano dziedziczenia. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Zwraca lub ustawia hiperlink zdefiniowany dla kliknięcia myszy. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Zwraca lub ustawia hiperlink zdefiniowany dla kliknięcia myszy. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Zwraca lub ustawia hiperlink zdefiniowany przy najechaniu myszą. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Zwraca lub ustawia hiperlink zdefiniowany przy najechaniu myszą. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Menedżer hiperłączy. Tylko do odczytu [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Zwraca:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

Pobiera efektywne dane formatowania części z zastosowanym dziedziczeniem.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).