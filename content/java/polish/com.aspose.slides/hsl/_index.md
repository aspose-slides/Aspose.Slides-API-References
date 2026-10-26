---
title: HSL
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Reprezentuje efekt odcienia/nasycenia/luminancji.
type: docs
url: /pl/com.aspose.slides/hsl/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Reprezentuje efekt odcień/nasycenie/luminancja. Odcień, nasycenie i luminancja mogą być każdorazowo dostosowywane względem bieżącej wartości.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera efektywne dane efektu odcień/nasycenie/luminancja z zastosowanym dziedziczeniem. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy podany [HSL](../../com.aspose.slides/hsl) jest równy bieżącemu [HSL](../../com.aspose.slides/hsl). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla danego typu. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```


Pobiera efektywne dane efektu odcień/nasycenie/luminancja z zastosowanym dziedziczeniem.

**Zwraca:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Określa, czy podany [HSL](../../com.aspose.slides/hsl) jest równy bieżącemu [HSL](../../com.aspose.slides/hsl).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | [HSL](../../com.aspose.slides/hsl) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Służy jako funkcja skrótu dla danego typu.

**Zwraca:**
int - kod skrótu dla bieżącego obiektu.