---
title: Duotone
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji API Java
description: Reprezentuje efekt duotonowy.
type: docs
url: /pl/com.aspose.slides/duotone/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Reprezentuje efekt duotonowy. Dla każdego piksela łączy Color1 i Color2 przez interpolację liniową, aby określić nowy kolor tego piksela.
## Metody

| Metoda | Opis |
| --- | --- |
| [getColor1()](#getColor1--) | Zwraca docelowy format koloru dla ciemnych pikseli. |
| [getColor2()](#getColor2--) | Zwraca docelowy format koloru dla jasnych pikseli. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane efektu duotonowego z zastosowaną dziedzicznością. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy określony [Duotone](../../com.aspose.slides/duotone) jest równy bieżącemu [Duotone](../../com.aspose.slides/duotone). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Zwraca docelowy format koloru dla ciemnych pikseli. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Zwraca docelowy format koloru dla jasnych pikseli. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Pobiera efektywne dane efektu duotonowego z zastosowaną dziedzicznością.

**Zwraca:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu long.

**Zwraca:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Określa, czy określony [Duotone](../../com.aspose.slides/duotone) jest równy bieżącemu [Duotone](../../com.aspose.slides/duotone).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt [Duotone](../../com.aspose.slides/duotone) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - Kod skrótu dla bieżącego obiektu.