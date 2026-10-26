---
title: PointCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje kolekci animačních bodů.
type: docs
url: /cs/com.aspose.slides/pointcollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Reprezentuje kolekci animačních bodů.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Vrací počet bodů v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Vrací bod na zadaném indexu. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


Vrací počet bodů v kolekci. Pouze pro čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


Vrací bod na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index prvku. |

**Vrací:**
[IPoint](../../com.aspose.slides/ipoint) - objekt [IPoint](../../com.aspose.slides/ipoint)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - java.util.Iterator pro celou kolekci.