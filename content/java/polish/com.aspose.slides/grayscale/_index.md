---
title: GrayScale
second_title: Aspose.Slides for Java – dokumentacja API
description: Reprezentuje efekt Skali Szarości.
type: docs
url: /pl/com.aspose.slides/grayscale/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Reprezentuje efekt Skali Szarości. Konwertuje wszystkie wartości kolorów efektu na odcień szarości, odpowiadający ich luminancji. Wartości alfa (przezroczystości) efektu pozostają niezmienione.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera efektywne dane efektu Skali Szarości z zastosowanym dziedziczeniem. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy określony [GrayScale](../../com.aspose.slides/grayscale) jest równy bieżącemu [GrayScale](../../com.aspose.slides/grayscale). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

Pobiera efektywne dane efektu Skali Szarości z zastosowanym dziedziczeniem.

**Zwraca:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - Obiekt [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy określony [GrayScale](../../com.aspose.slides/grayscale) jest równy bieżącemu [GrayScale](../../com.aspose.slides/grayscale).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt [GrayScale](../../com.aspose.slides/grayscale) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - Kod skrótu dla bieżącego obiektu.