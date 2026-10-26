---
title: PortionFormat
second_title: Aspose.Slides dla Androida – odniesienie do API Java
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
>  //Utwórz obiekt prezentacji, który reprezentuje plik prezentacji
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides używa tych specjalnych identyfikatorów (podobnych do używanych w PowerPoint):
>      // +mn-lt - Czcionka ciała Łacińska (Mniejsza czcionka Łacińska)
>      // +mj-lt -Czcionka nagłówka Łacińska (Główna czcionka Łacińska)
>      // +mn-ea - Czcionka ciała wschodnioazjatycka (Mniejsza czcionka wschodnioazjatycka)
>      // +mj-ea - Czcionka ciała wschodnioazjatycka (Mniejsza czcionka wschodnioazjatycka)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Ta klasa jest używana do zwracania i manipulowania właściwościami formatowania części tekstu zdefiniowanymi dla konkretnej części. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać efektywne wartości parametrów formatowania, w tym odziedziczone, należy użyć metody [getEffective](../../com.aspose.slides/portionformat\#getEffective), która zwraca instancję [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Tworzy nową instancję klasy [PortionFormat](../../com.aspose.slides/portionformat). |

## Metody

| Metoda | Opis |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Zwraca lub ustawia identyfikator zakładki. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Zwraca lub ustawia identyfikator zakładki. |
| [getSmartTagClean()](#getSmartTagClean--) | Określa, czy znacznik inteligentny powinien zostać wyczyszczony. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Określa, czy znacznik inteligentny powinien zostać wyczyszczony. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszy. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszy. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Menedżer hiperłączy. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane formatowania części z zastosowanym dziedziczeniem. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

Tworzy nową instancję klasy [PortionFormat](../../com.aspose.slides/portionformat).

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

Określa, czy znacznik inteligentny powinien zostać wyczyszczony. Nie stosuje się dziedziczenia. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

Określa, czy znacznik inteligentny powinien zostać wyczyszczony. Nie stosuje się dziedziczenia. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszy. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszy. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

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