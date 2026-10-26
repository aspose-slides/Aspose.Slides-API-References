---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje kolekci objektů GradientStopData.
type: docs
url: /cs/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

Reprezentuje kolekci objektů GradientStopData.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet gradientových zastávek v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Vrací gradientovou zastávku podle indexu. |
| [iterator()](#iterator--) | Vrací enumerátor, který iteruje přes kolekci. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopíruje všechny prvky z kolekce do určeného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (bezpečný pro vlákna). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
### size() {#size--}
```
public final int size()
```

Vrací počet gradientových zastávek v kolekci. Pouze ke čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

Vrací gradientovou zastávku podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

Vrací enumerátor, který iteruje přes kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - java.util.Iterator pro celou kolekci.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopíruje všechny prvky z kolekce do určeného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (bezpečný pro vlákna). Pouze ke čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze ke čtení Object.

**Vrací:**
java.lang.Object