---
title: GrayScale
second_title: Aspose.Slides dla Androida poprzez interfejs API Java
description: Reprezentuje efekt odcieni szarości.
type: docs
url: /pl/com.aspose.slides/grayscale/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Reprezentuje efekt odcieni szarości. Konwertuje wszystkie wartości kolorów efektu na odcień szarości, odpowiadający ich luminancji. Wartości alfa (przezroczystość) efektu pozostają niezmienione.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera efektywne dane efektu odcieni szarości z zastosowanym dziedziczeniem. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy podany [GrayScale](../../com.aspose.slides/grayscale) jest równy bieżącemu [GrayScale](../../com.aspose.slides/grayscale). |
| [hashCode()](#hashCode--) | Służy jako funkcja mieszająca dla określonego typu. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```


Pobiera efektywne dane efektu odcieni szarości z zastosowanym dziedziczeniem.

**Zwraca:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Określa, czy podany [GrayScale](../../com.aspose.slides/grayscale) jest równy bieżącemu [GrayScale](../../com.aspose.slides/grayscale).

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


Służy jako funkcja mieszająca dla określonego typu.

**Zwraca:**
int - Kod mieszający dla bieżącego obiektu.