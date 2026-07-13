---
title: AlphaFloor
second_title: Aspose.Slides dla Androida – dokumentacja API Java
description: Reprezentuje efekt Alpha Floor.
type: docs
url: /pl/com.aspose.slides/alphafloor/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Reprezentuje efekt Alpha Floor. Wartości Alpha (przezroczystość) mniejsze niż 100 % są zamieniane na zero. Innymi słowy, wszystko częściowo przezroczyste staje się całkowicie przezroczyste.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane efektu Alpha Floor z zastosowanym dziedziczeniem. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy podany [AlphaFloor](../../com.aspose.slides/alphafloor) jest równy bieżącemu [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Pobiera skuteczne dane efektu Alpha Floor z zastosowanym dziedziczeniem.

**Zwraca:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - A [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Określa, czy podany [AlphaFloor](../../com.aspose.slides/alphafloor) jest równy bieżącemu [AlphaFloor](../../com.aspose.slides/alphafloor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt [AlphaFloor](../../com.aspose.slides/alphafloor) do porównania. |

**Zwraca:**
boolean - true, jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - kod hash dla bieżącego obiektu.