---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides Java API-referencia
description: Megváltoztathatatlan objektum, amely egy csak olvasható kollekciót képvisel a hatékony képi transzformációs hatásokból.
type: docs
url: /hu/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

Immutábilis objektum, amely egy csak olvasható kollekciót képvisel a hatékony képi transzformációs hatásokból.

--------------------

Az IImageTransformOperationCollectionEffectiveData nevet IImageTransformOCollectionEffectiveData névre rövidítették, mivel a COM nevek hossza nem haladhatja meg a 39 karaktert.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben lévő képhatások számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az elemet az index alapján. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott objektum egyenlő-e a jelenlegi objektummal. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz, és alkalmas hash algoritmusokban és hash táblákat használó adatstruktúrákban. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely a kollekción iterál. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes kollekcióra. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a kollekció összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a kollekcióhoz való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérobjektumot. |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```


Visszaadja a képhatások számát a kollekcióban. Csak olvasható int.

**Visszatérési érték:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```


Visszaadja az elemet az index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatérési érték:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - a [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) objektum.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a megadott objektum egyenlő-e a jelenlegi objektummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Az objektum a jelenlegi objektummal való összehasonlításhoz. |

**Visszatérési érték:**
boolean – true, ha a megadott objektum egyenlő a jelenlegi objektummal; egyébként false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz, és alkalmas hash algoritmusokban és hash táblákat használó adatstruktúrákban.

**Visszatérési érték:**
int – egy hash kód a jelenlegi objektumhoz.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```


Visszaad egy enumerátort, amely a kollekción iterál.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> – egy IGenericEnumerator, amelyet a kollekció bejárására lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```


Visszaad egy java iterátort a teljes kollekcióra.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> – egy java.util.Iterator a teljes kollekcióhoz.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Átmásolja a kollekció összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Kitöltendő tömb. |
| index | int | Kezdőpozíció a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszaad egy értéket, amely jelzi, hogy a kollekcióhoz való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object