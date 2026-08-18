---
title: Luminance
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje efekt Luminancji.
type: docs
url: /pl/com.aspose.slides/luminance/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

Reprezentuje efekt Luminancji. Jasność liniowo przesuwa wszystkie kolory bliżej bieli lub czerni. Kontrast skalowanie wszystkich kolorów, aby były bliżej lub dalej od siebie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane efektu Luminancji z uwzględnionym dziedziczeniem. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy określony [Luminance](../../com.aspose.slides/luminance) jest równy bieżącemu [Luminance](../../com.aspose.slides/luminance). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```


Pobiera skuteczne dane efektu Luminancji z uwzględnionym dziedziczeniem.

**Zwraca:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - Obiekt [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Określa, czy określony [Luminance](../../com.aspose.slides/luminance) jest równy bieżącemu [Luminance](../../com.aspose.slides/luminance).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt [Luminance](../../com.aspose.slides/luminance) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - Kod skrótu dla bieżącego obiektu.