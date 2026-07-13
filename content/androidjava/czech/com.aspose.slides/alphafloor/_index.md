---
title: AlphaFloor
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje efekt Alpha Floor.
type: docs
url: /cs/com.aspose.slides/alphafloor/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechny implementované rozhraní:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Representuje efekt Alpha Floor. Hodnoty Alpha (průhlednost) menší než 100 % jsou změněny na nulu. Jinými slovy, vše, co je částečně průhledné, se stane zcela průhledným.

## Metody

| Metoda | Popis |
| --- | --- |
| [getEffective()](#getEffective--) | Získá data efektu Alpha Floor s aplikovaným děděním. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [AlphaFloor](../../com.aspose.slides/alphafloor) roven současnému [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |

### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

Získá data efektu Alpha Floor s aplikovaným děděním.

**Vrací:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - a [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda je zadaný [AlphaFloor](../../com.aspose.slides/alphafloor) roven současnému [AlphaFloor](../../com.aspose.slides/alphafloor).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaFloor](../../com.aspose.slides/alphafloor) k porovnání. |

**Vrací:**
boolean - true, pokud jsou objekty rovny; jinak false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int - hash kód pro aktuální objekt.