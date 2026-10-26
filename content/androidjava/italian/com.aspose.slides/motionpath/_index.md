---
title: MotionPath
second_title: Aspose.Slides per Android tramite il riferimento API Java
description: Rappresenta un percorso di movimento.
type: docs
url: /it/com.aspose.slides/motionpath/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Rappresenta il percorso di movimento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Aggiunge un nuovo comando al percorso |
| [getCount()](#getCount--) | Restituisce il numero di percorsi nella raccolta. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Inserisce un nuovo comando al percorso |
| [clear()](#clear--) | Rimuove tutti i comandi dalla raccolta. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Rimuove i comandi specificati dalla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un comando all'indice specificato. |
| [get_Item(int index)](#get-Item-int-) | Restituisce un comando all'indice specificato. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Aggiunge un nuovo comando al percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array di punti |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Booleano di coordinate relative |

**Restituisce:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Restituisce il numero di percorsi nella raccolta. Intero di sola lettura.

**Restituisce:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Inserisce un nuovo comando al percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero in cui l'elemento dovrebbe essere inserito. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array di punti |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Booleano di coordinate relative |

### clear() {#clear--}
```
public final void clear()
```


Rimuove tutti i comandi dalla raccolta.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Rimuove i comandi specificati dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Percorso di movimento da rimuovere. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove un comando all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un comando che deve essere eliminato. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Restituisce un comando all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento. |

**Restituisce:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - L'[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) oggetto.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Un java.util.Iterator per l'intera raccolta.