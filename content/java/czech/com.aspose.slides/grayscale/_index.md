---
title: GrayScale
second_title: Aspose.Slides pro Java API Reference
description: Představuje efekt stupně šedi.
type: docs
url: /cs/com.aspose.slides/grayscale/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechny implementované rozhraní:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Představuje efekt stupně šedi. Převádí všechny hodnoty barev efektu na odstín šedé odpovídající jejich jasu. Hodnoty alfa (průhlednosti) efektu nejsou ovlivněny.
## Metody

| Metoda | Popis |
| --- | --- |
| [getEffective()](#getEffective--) | Získá efektivní data efektu stupně šedi s aplikovaným děděním. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [GrayScale](../../com.aspose.slides/grayscale) roven aktuálnímu [GrayScale](../../com.aspose.slides/grayscale). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro určitý typ. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```


Získá efektivní data efektu stupně šedi s aplikovaným děděním.

**Vrací:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - A [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Určuje, zda je zadaný [GrayScale](../../com.aspose.slides/grayscale) roven aktuálnímu [GrayScale](../../com.aspose.slides/grayscale).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [GrayScale](../../com.aspose.slides/grayscale) k porovnání. |

**Vrací:**
boolean - true pokud jsou objekty stejné; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hashovací funkce pro určitý typ.

**Vrací:**
int - Hash kód pro aktuální objekt.