---
title: Duotone
second_title: Aspose.Slides pro Android pomocí Java API
description: Reprezentuje efekt Duotone.
type: docs
url: /cs/com.aspose.slides/duotone/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechny implementované rozhraní:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Představuje efekt Duotone. Pro každý pixel kombinuje Color1 a Color2 lineární interpolací k určení nové barvy pro tento pixel.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColor1()](#getColor1--) | Vrací cílový formát barvy pro tmavé pixely. |
| [getColor2()](#getColor2--) | Vrací cílový formát barvy pro světlé pixely. |
| [getEffective()](#getEffective--) | Získá data efektu Duotone s aplikovaným děděním. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je specifikovaný [Duotone](../../com.aspose.slides/duotone) roven aktuálnímu [Duotone](../../com.aspose.slides/duotone). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Vrací cílový formát barvy pro tmavé pixely. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Vrací cílový formát barvy pro světlé pixely. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Získá data efektu Duotone s aplikovaným děděním.

**Vrací:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
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


Určuje, zda je specifikovaný [Duotone](../../com.aspose.slides/duotone) roven aktuálnímu [Duotone](../../com.aspose.slides/duotone).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt [Duotone](../../com.aspose.slides/duotone) k porovnání. |

**Vrací:**
boolean - true pokud jsou objekty stejné; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int - Hash kód pro aktuální objekt.