---
title: IMasterSlide
second_title: Aspose.Slides dla Androida przy użyciu referencji API Javy
description: Reprezentuje slajd główny w prezentacji.
type: docs
url: /pl/com.aspose.slides/imasterslide/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Reprezentuje slajd główny w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżer HeaderFooter slajdu nadrzędnego. |
| [getTitleStyle()](#getTitleStyle--) | Zwraca styl tekstu tytułu. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Tworzy nowy slajd główny na podstawie bieżącego, stosując zewnętrzny motyw i stosuje utworzony slajd główny do wszystkich zależnych slajdów. |
| [getBodyStyle()](#getBodyStyle--) | Zwraca styl tekstu głównego. |
| [getOtherStyle()](#getOtherStyle--) | Zwraca styl innego tekstu. |
| [getLayoutSlides()](#getLayoutSlides--) | Zwraca kolekcję podrzędnych slajdów układu dla tego slajdu głównego. |
| [getPreserve()](#getPreserve--) | Określa, czy odpowiadający slajd główny jest usuwany, gdy wszystkie slajdy następujące po tym slajdzie głównym zostaną usunięte. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Określa, czy odpowiadający slajd główny jest usuwany, gdy wszystkie slajdy następujące po tym slajdzie głównym zostaną usunięte. |
| [hasDependingSlides()](#hasDependingSlides--) | Zwraca true, jeśli istnieje przynajmniej jeden slajd zależny od tego slajdu głównego. |
| [getDependingSlides()](#getDependingSlides--) | Zwraca tablicę wszystkich slajdów, które zależą od tego slajdu głównego. |
| [getDrawingGuides()](#getDrawingGuides--) | Zwraca kolekcję przewodników rysowania dla slajdu głównego. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Zwraca menedżer HeaderFooter slajdu nadrzędnego. Tylko do odczytu [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Zwraca:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Zwraca styl tekstu tytułu. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Tworzy nowy slajd główny na podstawie bieżącego, stosując zewnętrzny motyw i stosuje utworzony slajd główny do wszystkich zależnych slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do pliku zewnętrznego motywu (.thmx). |

**Zwraca:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nowy slajd główny z motywem.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Zwraca styl tekstu głównego. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Zwraca styl innego tekstu. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Zwraca kolekcję podrzędnych slajdów układu dla tego slajdu głównego. Tylko do odczytu [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Możesz uzyskać dostęp do alternatywnego API służącego do dodawania/wstawiania/usuwania/klonowania slajdów układu, używając właściwości ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Zwraca:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Określa, czy odpowiadający slajd główny jest usuwany, gdy wszystkie slajdy następujące po tym slajdzie głównym zostaną usunięte. Uwaga: Aspose.Slides nigdy nie usunie samodzielnie nieużywanego slajdu głównego; aby faktycznie usunąć nieużywane slajdy główne, wywołaj [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Boolean do odczytu i zapisu.

**Zwraca:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Określa, czy odpowiadający slajd główny jest usuwany, gdy wszystkie slajdy następujące po tym slajdzie głównym zostaną usunięte. Uwaga: Aspose.Slides nigdy nie usunie samodzielnie nieużywanego slajdu głównego; aby faktycznie usunąć nieużywane slajdy główne, wywołaj [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Boolean do odczytu i zapisu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Zwraca true, jeśli istnieje przynajmniej jeden slajd zależny od tego slajdu głównego. Boolean tylko do odczytu.

**Zwraca:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Zwraca tablicę wszystkich slajdów, które zależą od tego slajdu głównego.

**Zwraca:**
com.aspose.slides.ISlide[] - Tablica [ISlide](../../com.aspose.slides/islide), które zależą od tego slajdu głównego
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Zwraca kolekcję przewodników rysowania dla slajdu głównego. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Dodawanie nowej pionowej linii pomocniczej po prawej stronie środka slajdu
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)