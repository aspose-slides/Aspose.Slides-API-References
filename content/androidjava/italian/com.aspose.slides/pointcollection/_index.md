---
title: PointCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una raccolta di punti di animazione.
type: docs
url: /it/com.aspose.slides/pointcollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Rappresenta una raccolta di punti di animazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Restituisce il numero di punti nella raccolta. |
| [get_Item(int index)](#get-Item-int-) | Restituisce un punto all'indice specificato. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iterator java per l'intera raccolta. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


Restituisce il numero di punti nella raccolta. int di sola lettura.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


Restituisce un punto all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento. |

**Restituisce:**
[IPoint](../../com.aspose.slides/ipoint) - L'oggetto [IPoint](../../com.aspose.slides/ipoint).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


Restituisce un iterator java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Un java.util.Iterator per l'intera raccolta.