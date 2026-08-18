---
title: AlphaModulateFixed
second_title: Aspose.Slides Java API referencia
description: Reprezentálja az Alpha Modulate Fixed hatást.
type: docs
url: /hu/com.aspose.slides/alphamodulatefixed/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

Alpha Modulate Fixed hatást reprezentál. A hatás alfa (átlátszóság) értékei egy rögzített százalékkal szorzódnak.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAmount()](#getAmount--) | Visszaadja a hatás mennyiségét százalékban. |
| [setAmount(float value)](#setAmount-float-) | Visszaadja a hatás mennyiségét százalékban. |
| [getEffective()](#getEffective--) | Lekéri a hatékony Alpha Modulate Fixed hatás adatokat, az öröklődés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) egyenlő-e a jelenlegi [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed). |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getAmount() {#getAmount--}
```
public final float getAmount()
```

Visszaadja a hatás mennyiségét százalékban. Olvasható/írási float.

**Visszatér:**
float
### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```

Visszaadja a hatás mennyiségét százalékban. Olvasható/írási float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```

Lekéri a hatékony Alpha Modulate Fixed hatás adatokat, az öröklődés alkalmazásával.

**Visszatér:**
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - A [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a megadott [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) egyenlő-e a jelenlegi [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed), amivel összehasonlítja. |

**Visszatér:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatér:**
int - Egy hash kód a jelenlegi objektumhoz.