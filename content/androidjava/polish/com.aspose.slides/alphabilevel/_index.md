---
title: AlphaBiLevel
second_title: Aspose.Slides dla Androida - dokumentacja API Java
description: Reprezentuje efekt Alpha Bi-Level.
type: docs
url: /pl/com.aspose.slides/alphabilevel/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Reprezentuje efekt Alpha Bi-Level. Wartości Alpha (Opacity) mniejsze niż próg są zmieniane na 0 (całkowicie przezroczyste), a wartości Alpha większe lub równe progowi są zmieniane na 100 % (całkowicie nieprzezroczyste).

## Metody

| Metoda | Opis |
| --- | --- |
| [getThreshold()](#getThreshold--) | Zwraca próg efektu. |
| [setThreshold(float value)](#setThreshold-float-) | Zwraca próg efektu. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane efektu Alpha Bi-Level z zastosowanym dziedziczeniem. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy określony [AlphaBiLevel](../../com.aspose.slides/alphabilevel) jest równy bieżącemu [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |

### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Zwraca próg efektu. Odczyt/zapis float.

**Zwraca:**
float

### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Zwraca próg efektu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Pobiera skuteczne dane efektu Alpha Bi-Level z zastosowanym dziedziczeniem.

**Zwraca:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy określony [AlphaBiLevel](../../com.aspose.slides/alphabilevel) jest równy bieżącemu [AlphaBiLevel](../../com.aspose.slides/alphabilevel).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt [AlphaBiLevel](../../com.aspose.slides/alphabilevel) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - Kod skrótu dla bieżącego obiektu.