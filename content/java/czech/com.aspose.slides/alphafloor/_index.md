---
title: AlphaFloor
second_title: Aspose.Slides pro Java API Reference
description: Představuje efekt Alpha Floor.
type: docs
url: /cs/com.aspose.slides/alphafloor/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Reprezentuje efekt Alpha Floor. Hodnoty Alpha (průhlednosti) menší než 100 % jsou změněny na nulu. Jinými slovy se všechno částečně průhledné stane zcela průhledným.
## Metody

| Metoda | Popis |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Floor effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaFloor](../../com.aspose.slides/alphafloor) is equal to the current [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Získá efektivní data efektu Alpha Floor s aplikovanou dědičností.

**Návratová hodnota:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - A [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Určuje, zda je zadaný [AlphaFloor](../../com.aspose.slides/alphafloor) roven aktuálnímu [AlphaFloor](../../com.aspose.slides/alphafloor).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaFloor](../../com.aspose.slides/alphafloor) k porovnání. |

**Návratová hodnota:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hashovací funkce pro konkrétní typ.

**Návratová hodnota:**
int - A hash code for the current object.