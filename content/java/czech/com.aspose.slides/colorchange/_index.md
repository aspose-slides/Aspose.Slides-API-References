---
title: ColorChange
second_title: Aspose.Slides pro Java – Reference API
description: Reprezentuje efekt změny barvy.
type: docs
url: /cs/com.aspose.slides/colorchange/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechny implementované rozhraní:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Reprezentuje efekt změny barvy. Instance FromColor jsou nahrazeny instancemi ToColor.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFromColor()](#getFromColor--) | Barva, která bude nahrazena. |
| [getToColor()](#getToColor--) | Barva, která nahradí. |
| [getEffective()](#getEffective--) | Získá efektivní data efektu změny barvy s aplikovaným děděním. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [ColorChange](../../com.aspose.slides/colorchange) roven aktuálnímu [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

Barva, která bude nahrazena. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

Barva, která nahradí. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

Získá efektivní data efektu změny barvy s aplikovaným děděním.

**Vrací:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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

Určuje, zda je zadaný [ColorChange](../../com.aspose.slides/colorchange) roven aktuálnímu [ColorChange](../../com.aspose.slides/colorchange).

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Porovnávaný [ColorChange](../../com.aspose.slides/colorchange). |

**Vrací:**
boolean - true pokud jsou objekty rovny; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int - Hash kód pro aktuální objekt.