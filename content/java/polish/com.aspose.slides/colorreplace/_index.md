---
title: ColorReplace
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje efekt zamiany koloru.
type: docs
url: /pl/com.aspose.slides/colorreplace/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Reprezentuje efekt zamiany koloru. Wszystkie kolory efektu są zamieniane na stały kolor. Wartości alfa pozostają niezmienione.
## Metody

| Metoda | Opis |
| --- | --- |
| [getColor()](#getColor--) | Zwraca format koloru, który zastąpi kolor każdego piksela. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane efektu zamiany koloru z zastosowanym dziedziczeniem. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy podany [ColorReplace](../../com.aspose.slides/colorreplace) jest równy bieżącemu [ColorReplace](../../com.aspose.slides/colorreplace). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Zwraca format koloru, który zastąpi kolor każdego piksela. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```


Pobiera skuteczne dane efektu zamiany koloru z zastosowanym dziedziczeniem.

**Zwraca:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - a [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
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


Określa, czy podany [ColorReplace](../../com.aspose.slides/colorreplace) jest równy bieżącemu [ColorReplace](../../com.aspose.slides/colorreplace).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | [ColorReplace](../../com.aspose.slides/colorreplace) do porównania. |

**Zwraca:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - kod hash dla bieżącego obiektu.