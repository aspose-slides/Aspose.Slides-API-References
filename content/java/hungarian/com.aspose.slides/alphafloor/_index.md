---
title: AlphaFloor
second_title: Aspose.Slides for Java API Referencia
description: Alpha Floor effektust ábrázol.
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

Ábrázol egy Alpha Floor effect-et. Az 100%-nál kisebb Alpha (átlátszatlanság) értékek nullára változnak. Más szóval, minden részben átlátszó teljesen átlátszóvá válik.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony Alpha Floor effect adatot az öröklődés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Meghatározza, hogy a megadott [AlphaFloor](../../com.aspose.slides/alphafloor) egyenlő-e a jelenlegi [AlphaFloor](../../com.aspose.slides/alphafloor)-vel. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

Lekéri a hatékony Alpha Floor effect adatot az öröklődés alkalmazásával.

**Visszatérési érték:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - A [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Meghatározza, hogy a megadott [AlphaFloor](../../com.aspose.slides/alphafloor) egyenlő-e a jelenlegi [AlphaFloor](../../com.aspose.slides/alphafloor)-vel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [AlphaFloor](../../com.aspose.slides/alphafloor) az összehasonlításhoz. |

**Visszatérési érték:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - Az aktuális objektum hash kódja.