---
title: ColorReplace
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje efekt náhrady barvy.
type: docs
url: /cs/com.aspose.slides/colorreplace/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Představuje efekt náhrady barvy. Všechny barvy efektu jsou změněny na pevnou barvu. Hodnoty alfa zůstávají nedotčeny.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColor()](#getColor--) | Vrací formát barvy, který nahradí barvu každého pixelu. |
| [getEffective()](#getEffective--) | Získá efektivní data efektu náhrady barvy s použitím dědičnosti. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [ColorReplace](../../com.aspose.slides/colorreplace) roven aktuálnímu [ColorReplace](../../com.aspose.slides/colorreplace). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Vrací formát barvy, který nahradí barvu každého pixelu. Pouze ke čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Získá efektivní data efektu náhrady barvy s použitím dědičnosti.

**Vrací:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - Jedná se o [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze ke čtení long.

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
| obj | java.lang.Object | Objekt [ColorReplace](../../com.aspose.slides/colorreplace) k porovnání. |

**Vrací:**
boolean - true pokud jsou objekty stejné; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int - hash kód pro aktuální objekt.