---
title: AlphaModulate
second_title: Aspose.Slides Androidra a Java API-referencia alapján
description: Az Alpha Modulate effektust reprezentálja.
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

Az Alpha Modulate effektust reprezentálja. Az effektus alfa (átlátszóság) értékeit egy rögzített százalékkal szorozzák. Az effektus konténer egy olyan effektust ad meg, amely alfa értékeket tartalmaz a moduláláshoz.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony Alpha Modulate effektus adatát az öröklődés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [AlphaModulate](../../com.aspose.slides/alphamodulate) egyenlő-e a jelenlegi [AlphaModulate](../../com.aspose.slides/alphamodulate)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```

Lekéri a hatékony Alpha Modulate effektus adatát az öröklődés alkalmazásával.

**Visszatérési érték:**  
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - Egy [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a megadott [AlphaModulate](../../com.aspose.slides/alphamodulate) egyenlő-e a jelenlegi [AlphaModulate](../../com.aspose.slides/alphamodulate)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [AlphaModulate](../../com.aspose.slides/alphamodulate) a összehasonlításhoz. |

**Visszatérési érték:**  
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**  
int - Egy hash kód a jelenlegi objektumhoz.