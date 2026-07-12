---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides Android-hoz a Java API Referencián keresztül
description: Megváltoztathatatlan objektum, amely egy csak olvasható hatékony képek transzformációs effektusok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

Immutable objektum, amely egy csak olvasható hatékony képek transzformációs effektusok gyűjteményét képviseli.

--------------------

Az IImageTransformOperationCollectionEffectiveData név le lett rövidítve IImageTransformOCollectionEffectiveData-re, mivel a COM nevek hossza nem lehet nagyobb, mint 39.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a képeffektusok számát egy gyűjteményben. |
| [get_Item(int index)](#get-Item-int-) | Visszaad elemet az index szerint. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott objektum egyenlő-e a jelenlegi objektummal. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és adatszerkezetekben, például hash táblában való használatra. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort az egész gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | A gyűjtemény összes elemét átmásolja a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérobjektumot. |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```


Visszaadja a képeffektusok számát egy gyűjteményben. Csak olvasható int.

**Visszatérési érték:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```


Visszaad elemet az index szerint.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatérési érték:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - A [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) objektum.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a megadott objektum egyenlő-e a jelenlegi objektummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Az objektum, amellyel a jelenlegi objektumot összehasonlítják. |

**Visszatérési érték:**
boolean - igaz, ha a megadott objektum egyenlő a jelenlegi objektummal; különben hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és adatszerkezetekben, például hash táblában való használatra.

**Visszatérési érték:**
int - Egy hash kód a jelenlegi objektumhoz.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```


Visszaad egy Java iterátort az egész gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - Egy java.util.Iterator az egész gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


A gyűjtemény összes elemét átmásolja a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Kitöltendő tömb. |
| index | int | Kezdő pozíció a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object