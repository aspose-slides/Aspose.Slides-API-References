---
title: ColorReplace
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje efekt nahrazení barvy.
type: docs
url: /cs/com.aspose.slides/colorreplace/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechny implementované rozhraní:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Reprezentuje efekt Nahrazení barvy. Všechny barvy efektu jsou změněny na pevnou barvu. Hodnoty alfa zůstávají nezměněny.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColor()](#getColor--) | Returns color format which will replace color of every pixel. |
| [getEffective()](#getEffective--) | Gets effective Color Replacement effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [ColorReplace](../../com.aspose.slides/colorreplace) is equal to the current [ColorReplace](../../com.aspose.slides/colorreplace). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Vrací formát barvy, který nahradí barvu každého pixelu. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```


Získá efektivní data efektu Color Replacement s aplikovanou dědičností.

**Vrací:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verze. Pouze pro čtení long.

**Vrací:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Určuje, zda je zadaný [ColorReplace](../../com.aspose.slides/colorreplace) roven aktuálnímu [ColorReplace](../../com.aspose.slides/colorreplace).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt [ColorReplace](../../com.aspose.slides/colorreplace) pro porovnání. |

**Vrací:**
boolean - true pokud jsou objekty si rovny; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hash funkce pro konkrétní typ.

**Vrací:**
int - Hash kód pro aktuální objekt.