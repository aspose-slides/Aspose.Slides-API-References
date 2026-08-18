---
title: AlphaBiLevel
second_title: Aspose.Slides Java API Referenciája
description: Az Alpha Bi-Level effektust reprezentálja.
type: docs
url: /hu/com.aspose.slides/alphabilevel/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**  
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect  
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Az Alpha Bi-Level effektust reprezentálja. Az alfa (átlátszóság) értékek, amelyek kisebbek a küszöbnél, 0-ra (teljesen átlátszó) változnak, a küszögnél nagyobb vagy egyenlő alfa értékek pedig 100 % (teljesen átlátszatlan) lesznek.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getThreshold()](#getThreshold--) | Visszaadja a hatás küszöböt. |
| [setThreshold(float value)](#setThreshold-float-) | Visszaadja a hatás küszöböt. |
| [getEffective()](#getEffective--) | Az öröklődéssel alkalmazott hatékony Alpha Bi-Level effektus adatot adja vissza. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [AlphaBiLevel](../../com.aspose.slides/alphabilevel) egyenlő-e a jelenlegi [AlphaBiLevel](../../com.aspose.slides/alphabilevel)-vel. |
| [hashCode()](#hashCode--) | Hash-függvényként szolgál egy adott típushoz. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


Visszaadja a hatás küszöböt. Olvasás/írás float.

**Visszatérési érték:**  
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


Visszaadja a hatás küszöböt. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


Az öröklődéssel alkalmazott hatékony Alpha Bi-Level effektus adatot adja vissza.

**Visszatérési érték:**  
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) – egy [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a megadott [AlphaBiLevel](../../com.aspose.slides/alphabilevel) egyenlő-e a jelenlegi [AlphaBiLevel](../../com.aspose.slides/alphabilevel)-vel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [AlphaBiLevel](../../com.aspose.slides/alphabilevel) a összehasonlításhoz. |

**Visszatérési érték:**  
boolean – igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash-függvényként szolgál egy adott típushoz.

**Visszatérési érték:**  
int – egy hash kód a jelenlegi objektumhoz.