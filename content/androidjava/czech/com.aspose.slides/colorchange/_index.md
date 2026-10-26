---
title: ColorChange
second_title: Aspose.Slides pro Android přes referenci Java API
description: Představuje efekt změny barvy.
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

Představuje efekt změny barvy. Instance FromColor jsou nahrazeny instancemi ToColor.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color, která bude nahrazena. |
| [getToColor()](#getToColor--) | Color, která bude nahrazovat. |
| [getEffective()](#getEffective--) | Získává efektivní data změny barvy s aplikovaným děděním. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je specifikovaný [ColorChange](../../com.aspose.slides/colorchange) roven aktuálnímu [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Slouží jako hašovací funkce pro konkrétní typ. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```


Color, která bude nahrazena. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```


Color, která nahradí. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```


Získává efektivní data změny barvy s aplikovaným děděním.

**Vrací:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - A [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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


Určuje, zda je specifikovaný [ColorChange](../../com.aspose.slides/colorchange) roven aktuálnímu [ColorChange](../../com.aspose.slides/colorchange).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [ColorChange](../../com.aspose.slides/colorchange) k porovnání. |

**Vrací:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hašovací funkce pro konkrétní typ.

**Vrací:**
int - Hašovací kód pro aktuální objekt.