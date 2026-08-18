---
title: MasterSlide
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje slajd master w prezentacji.
type: docs
url: /pl/com.aspose.slides/masterslide/
---
**Dziedziczenie:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)  
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Reprezentuje slajd master w prezentacji.

## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżer HeaderFooter slajdu master. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Tworzy nowy slajd master na podstawie bieżącego, stosując zewnętrzny motyw i stosuje utworzony slajd master do wszystkich zależnych slajdów. |
| [getTitleStyle()](#getTitleStyle--) | Zwraca styl tekstu tytułu. |
| [getBodyStyle()](#getBodyStyle--) | Zwraca styl tekstu głównego. |
| [getOtherStyle()](#getOtherStyle--) | Zwraca styl innego tekstu. |
| [getLayoutSlides()](#getLayoutSlides--) | Zwraca kolekcję potomnych slajdów układu dla tego slajdu master. |
| [getPreserve()](#getPreserve--) | Określa, czy odpowiedni master zostanie usunięty, gdy wszystkie slajdy po nim zostaną usunięte. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Określa, czy odpowiedni master zostanie usunięty, gdy wszystkie slajdy po nim zostaną usunięte. |
| [getDependingSlides()](#getDependingSlides--) | Zwraca tablicę ze wszystkimi slajdami, które zależą od tego slajdu master. |
| [hasDependingSlides()](#hasDependingSlides--) | Zwraca wartość true, jeśli istnieje przynajmniej jeden slajd zależący od tego slajdu master. |
| [getThemeManager()](#getThemeManager--) | Zwraca menedżer motywu. |
| [getName()](#getName--) | Zwraca lub ustawia nazwę slajdu master. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca lub ustawia nazwę slajdu master. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na slajdzie master mają być wyświetlane na slajdach. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na slajdzie master mają być wyświetlane na slajdach. |
| [getDrawingGuides()](#getDrawingGuides--) | Zwraca kolekcję przewodników rysowania dla slajdu master. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Zwraca menedżer HeaderFooter slajdu master. Tylko do odczytu [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Zwraca:**  
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Tworzy nowy slajd master na podstawie bieżącego, stosując zewnętrzny motyw i stosuje utworzony slajd master do wszystkich zależnych slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do pliku zewnętrznego motywu (.thmx). |

**Zwraca:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) – nowy slajd master z motywem.

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Zwraca styl tekstu tytułu. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Zwraca styl tekstu głównego. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Zwraca styl innego tekstu. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Zwraca kolekcję potomnych slajdów układu dla tego slajdu master. Tylko do odczytu [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Możesz uzyskać dostęp do alternatywnego API służącego do dodawania/wstawiania/usuwania/kopiowania slajdów układu, używając właściwości ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Zwraca:**  
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Określa, czy odpowiedni master zostanie usunięty, gdy wszystkie slajdy po nim zostaną usunięte. Uwaga: Aspose.Slides nigdy nie usunie samodzielnie nieużywanego mastera; aby faktycznie usunąć nieużywane mastery, wywołaj [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Odczyt/Zapis  boolean .

**Zwraca:**  
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Określa, czy odpowiedni master zostanie usunięty, gdy wszystkie slajdy po nim zostaną usunięte. Uwaga: Aspose.Slides nigdy nie usunie samodzielnie nieużywanego mastera; aby faktycznie usunąć nieużywane mastery, wywołaj [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Odczyt/Zapis  boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Zwraca tablicę ze wszystkimi slajdami, które zależą od tego slajdu master.

**Zwraca:**  
com.aspose.slides.ISlide[] - Tablica [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Zwraca wartość true, jeśli istnieje przynajmniej jeden slajd zależący od tego slajdu master. Tylko do odczytu  boolean .

**Zwraca:**  
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Zwraca menedżer motywu. Tylko do odczytu [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Zwraca:**  
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

Zwraca lub ustawia nazwę slajdu master. Odczyt/Zapis String.

**Zwraca:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Zwraca lub ustawia nazwę slajdu master. Odczyt/Zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Określa, czy kształty na slajdzie master mają być wyświetlane na slajdach. Dla samego slajdu master ta właściwość zawsze zwraca false. Odczyt/Zapis  boolean .

**Zwraca:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Określa, czy kształty na slajdzie master mają być wyświetlane na slajdach. Dla samego slajdu master ta właściwość zawsze zwraca false. Odczyt/Zapis  boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Zwraca kolekcję przewodników rysowania dla slajdu master. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Dodawanie nowej pionowej linii prowadzacej po prawej stronie środka slajdu
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)