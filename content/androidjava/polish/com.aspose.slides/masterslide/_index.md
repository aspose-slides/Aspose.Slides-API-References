---
title: MasterSlide
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje slajd-mistrz w prezentacji.
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

Reprezentuje slajd-mistrz w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera HeaderFooter slajdu-mistrza. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Tworzy nowy slajd-mistrz na podstawie bieżącego, stosując zewnętrzny motyw i stosuje utworzony slajd-mistrz do wszystkich zależnych slajdów. |
| [getTitleStyle()](#getTitleStyle--) | Zwraca styl tekstu tytułu. |
| [getBodyStyle()](#getBodyStyle--) | Zwraca styl tekstu głównego. |
| [getOtherStyle()](#getOtherStyle--) | Zwraca styl innego tekstu. |
| [getLayoutSlides()](#getLayoutSlides--) | Zwraca kolekcję podrzędnych slajdów-układu dla tego slajdu-mistrza. |
| [getPreserve()](#getPreserve--) | Określa, czy odpowiedni slajd-mistrz jest usuwany, gdy wszystkie slajdy następujące po tym slajdzie-mistrzu zostaną usunięte. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Określa, czy odpowiedni slajd-mistrz jest usuwany, gdy wszystkie slajdy następujące po tym slajdzie-mistrzu zostaną usunięte. |
| [getDependingSlides()](#getDependingSlides--) | Zwraca tablicę ze wszystkimi slajdami, które zależą od tego slajdu-mistrza. |
| [hasDependingSlides()](#hasDependingSlides--) | Zwraca true, jeśli istnieje co najmniej jeden slajd zależny od tego slajdu-mistrza. |
| [getThemeManager()](#getThemeManager--) | Zwraca menedżera motywów. |
| [getName()](#getName--) | Zwraca lub ustawia nazwę slajdu-mistrza. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca lub ustawia nazwę slajdu-mistrza. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na slajdzie-mistrzu mają być wyświetlane na slajdach. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na slajdzie-mistrzu mają być wyświetlane na slajdach. |
| [getDrawingGuides()](#getDrawingGuides--) | Zwraca kolekcję przewodników rysowania dla slajdu-mistrza. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Zwraca menedżera HeaderFooter slajdu-mistrza. Tylko do odczytu [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Zwraca:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Tworzy nowy slajd-mistrz na podstawie bieżącego, stosując zewnętrzny motyw, i stosuje utworzony slajd-mistrz do wszystkich zależnych slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do pliku zewnętrznego motywu (.thmx). |

**Zwraca:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nowy MasterSlide z motywem.

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

Zwraca kolekcję podrzędnych slajdów-układu dla tego slajdu-mistrza. Tylko do odczytu [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Można uzyskać dostęp do alternatywnego API umożliwiającego dodawanie/wstawianie/usuwanie/klonowanie slajdów-układu przy użyciu właściwości ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Zwraca:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Określa, czy odpowiadający slajd-mistrz jest usuwany, gdy wszystkie slajdy następujące po tym slajdzie-mistrzu zostaną usunięte. Uwaga: Aspose.Slides nigdy nie usuwa nieużywanego slajdu-mistrza samodzielnie; aby rzeczywiście usunąć nieużywane slajdy-mistrze, wywołaj [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Odczyt/zapis  boolean .

**Zwraca:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Określa, czy odpowiadający slajd-mistrz jest usuwany, gdy wszystkie slajdy następujące po tym slajdzie-mistrzu zostaną usunięte. Uwaga: Aspose.Slides nigdy nie usuwa nieużywanego slajdu-mistrza samodzielnie; aby rzeczywiście usunąć nieużywane slajdy-mistrze, wywołaj [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Odczyt/zapis  boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Zwraca tablicę ze wszystkimi slajdami, które zależą od tego slajdu-mistrza.

**Zwraca:**
com.aspose.slides.ISlide[] - Tablica [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Zwraca true, jeśli istnieje co najmniej jeden slajd zależny od tego slajdu-mistrza. Tylko do odczytu  boolean .

**Zwraca:**
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Zwraca menedżera motywów. Tylko do odczytu [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Zwraca:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

Zwraca lub ustawia nazwę slajdu-mistrza. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Zwraca lub ustawia nazwę slajdu-mistrza. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Określa, czy kształty na slajdzie-mistrzu mają być wyświetlane na slajdach. Dla samego slajdu-mistrza ta właściwość zawsze zwraca  false . Odczyt/zapis  boolean .

**Zwraca:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Określa, czy kształty na slajdzie-mistrzu mają być wyświetlane na slajdach. Dla samego slajdu-mistrza ta właściwość zawsze zwraca  false . Odczyt/zapis  boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Zwraca kolekcję przewodników rysowania dla slajdu-mistrza. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Dodawanie nowej pionowej linii prowadzącej po prawej stronie środka slajdu
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)