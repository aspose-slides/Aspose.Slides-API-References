---
title: AlphaFloor
second_title: Referencja API Aspose.Slides dla Javy
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

Reprezentuje efekt Alpha Floor. Wartości alfa (przezroczystość) mniejsze niż 100% są zmieniane na zero. Inaczej mówiąc, wszystko częściowo przezroczyste staje się całkowicie przezroczyste.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Floor effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaFloor](../../com.aspose.slides/alphafloor) is equal to the current [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
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

Określa, czy określony [AlphaFloor](../../com.aspose.slides/alphafloor) jest równy bieżącemu [AlphaFloor](../../com.aspose.slides/alphafloor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaFloor](../../com.aspose.slides/alphafloor) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - Kod skrótu dla bieżącego obiektu.