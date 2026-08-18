---
title: ColorChange
second_title: Aspose.Slides dla Java – referencja API
description: Reprezentuje efekt zmiany koloru.
type: docs
url: /pl/com.aspose.slides/colorchange/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Reprezentuje efekt Zmiany Koloru. Instancje FromColor są zastępowane instancjami ToColor.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFromColor()](#getFromColor--) | Kolor, który zostanie zastąpiony. |
| [getToColor()](#getToColor--) | Kolor, który zastąpi. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane efektu Zmiany Koloru z zastosowanym odziedziczeniem. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy podany [ColorChange](../../com.aspose.slides/colorchange) jest równy bieżącemu [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Służy jako funkcja hash dla określonego typu. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```


Kolor, który zostanie zastąpiony. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```


Kolor, który zastąpi. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```


Pobiera efektywne dane efektu Zmiany Koloru z zastosowanym odziedziczeniem.

**Zwraca:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - A [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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


Określa, czy podany [ColorChange](../../com.aspose.slides/colorchange) jest równy bieżącemu [ColorChange](../../com.aspose.slides/colorchange).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | [ColorChange](../../com.aspose.slides/colorchange) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Służy jako funkcja hash dla określonego typu.

**Zwraca:**
int - Kod hash dla bieżącego obiektu.