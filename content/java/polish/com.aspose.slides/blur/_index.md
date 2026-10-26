---
title: Blur
second_title: Aspose.Slides dla Java – odniesienie do API
description: Reprezentuje efekt rozmycia, który jest stosowany do całego kształtu, włącznie z jego wypełnieniem.
type: docs
url: /pl/com.aspose.slides/blur/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Reprezentuje efekt Blur, który jest stosowany do całego kształtu, włącznie z jego wypełnieniem. Wszystkie kanały kolorów, w tym alfa, są dotknięte.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRadius()](#getRadius--) | Zwraca lub ustawia promień rozmycia. |
| [setRadius(double value)](#setRadius-double-) | Zwraca lub ustawia promień rozmycia. |
| [getGrow()](#getGrow--) | Określa, czy granice obiektu powinny być powiększane w wyniku rozmycia. |
| [setGrow(boolean value)](#setGrow-boolean-) | Określa, czy granice obiektu powinny być powiększane w wyniku rozmycia. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane efektu Blur z zastosowanym dziedziczeniem. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy określony [Blur](../../com.aspose.slides/blur) jest równy bieżącemu [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Zwraca lub ustawia promień rozmycia. Odczyt/zapis double.

**Zwraca:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Zwraca lub ustawia promień rozmycia. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```


Określa, czy granice obiektu powinny być powiększane w wyniku rozmycia. Prawda wskazuje, że granice są powiększane, a fałsz, że nie są. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```


Określa, czy granice obiektu powinny być powiększane w wyniku rozmycia. Prawda wskazuje, że granice są powiększane, a fałsz, że nie są. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```


Pobiera efektywne dane efektu Blur z zastosowanym dziedziczeniem.

**Zwraca:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Określa, czy określony [Blur](../../com.aspose.slides/blur) jest równy bieżącemu [Blur](../../com.aspose.slides/blur).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt [Blur](../../com.aspose.slides/blur) do porównania. |

**Zwraca:**
boolean - prawda, jeśli obiekty są równe; w przeciwnym razie fałsz.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - Kod skrótu dla bieżącego obiektu.