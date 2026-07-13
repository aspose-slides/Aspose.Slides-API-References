---
title: BiLevel
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Reprezentuje efekt dwupoziomowy czarno-biały.
type: docs
url: /pl/com.aspose.slides/bilevel/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Reprezentuje efekt dwupoziomowy (czarny/biały). Kolory wejściowe, których luminancja jest mniejsza niż określona wartość progowa, są zmieniane na czarny. Kolory wejściowe, których luminancja jest większa lub równa określonej wartości, są ustawiane na biały. Wartości efektu alfa nie są zmieniane przez ten efekt.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane efektu Bi-Level z zastosowanym dziedziczeniem. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy podany [BiLevel](../../com.aspose.slides/bilevel) jest równy bieżącemu [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Pobiera skuteczne dane efektu Bi-Level z zastosowanym dziedziczeniem.

**Zwraca:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy podany [BiLevel](../../com.aspose.slides/bilevel) jest równy bieżącemu [BiLevel](../../com.aspose.slides/bilevel).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | [BiLevel](../../com.aspose.slides/bilevel) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - Kod skrótu dla bieżącego obiektu.