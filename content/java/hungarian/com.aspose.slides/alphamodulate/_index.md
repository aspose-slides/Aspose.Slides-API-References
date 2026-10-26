---
title: AlphaModulate
second_title: Aspose.Slides Java API hivatkozás
description: Ábrázolja az Alpha Modulate hatást.
type: docs
url: /hu/com.aspose.slides/alphamodulate/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

Ábrázolja az Alpha Modulate hatást. A hatás alfa (átlátszóság) értékei egy rögzített százalékkal szorzódnak. A hatástartó meghatározza azt a hatást, amely alfa értékeket tartalmaz a moduláláshoz.
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony Alpha Modulate hatás adatokat, az öröklés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Meghatározza, hogy a megadott [AlphaModulate](../../com.aspose.slides/alphamodulate) egyenlő-e a jelenlegi [AlphaModulate](../../com.aspose.slides/alphamodulate)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```


Lekéri a hatékony Alpha Modulate hatás adatokat, az öröklés alkalmazásával.

**Visszatér:**
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - A [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Meghatározza, hogy a megadott [AlphaModulate](../../com.aspose.slides/alphamodulate) egyenlő-e a jelenlegi [AlphaModulate](../../com.aspose.slides/alphamodulate)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [AlphaModulate](../../com.aspose.slides/alphamodulate) a összehasonlításhoz. |

**Visszatér:**
boolean - true, ha az objektumok egyenlőek; egyébként false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz.

**Visszatér:**
int - Egy hash kód a jelenlegi objektumhoz.