---
title: AlphaFloor
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Alpha Floor hatást reprezentál.
type: docs
url: /hu/com.aspose.slides/alphafloor/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Alpha Floor hatást reprezentál. Az 100%-nál kisebb alfa (átlátszóság) értékek nullára változnak. Más szóval, minden részben átlátszó objektum teljesen átlátszóvá válik.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony Alpha Floor hatásadatokat az öröklődés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [AlphaFloor](../../com.aspose.slides/alphafloor) egyenlő-e a jelenlegi [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

Lekéri a hatékony Alpha Floor hatásadatokat az öröklődés alkalmazásával.

**Visszatérési érték:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - A [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a megadott [AlphaFloor](../../com.aspose.slides/alphafloor) egyenlő-e a jelenlegi [AlphaFloor](../../com.aspose.slides/alphafloor).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaFloor](../../com.aspose.slides/alphafloor) az összehasonlításhoz. |

**Visszatérési érték:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - Egy hash kód a jelenlegi objektumhoz.