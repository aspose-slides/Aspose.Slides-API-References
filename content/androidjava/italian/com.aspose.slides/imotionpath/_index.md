---
title: IMotionPath
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta il percorso di movimento.
type: docs
url: /it/com.aspose.slides/imotionpath/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath)
```

Rappresenta il percorso di movimento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Aggiunge un nuovo comando al percorso |
| [getCount()](#getCount--) | Restituisce il numero di percorsi nella collezione. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Inserisce un nuovo comando al percorso |
| [clear()](#clear--) | Rimuove tutti i comandi dalla collezione. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Rimuove i comandi specificati dalla collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un comando all'indice specificato. |
| [get_Item(int index)](#get-Item-int-) | Restituisce un comando all'indice specificato. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Aggiunge un nuovo comando al percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Tipo di comando per il comportamento dell'effetto di movimento dell'animazione [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array di punti android.graphics.PointF[] |
| ptsType | int | Tipo di punti nel percorso di movimento dell'animazione [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indica se utilizzare coordinate relative o no boolean |

**Restituisce:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Comando di un percorso [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Restituisce il numero di percorsi nella collezione. Solo lettura int.

**Restituisce:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Inserisce un nuovo comando al percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice per l'inserimento del comando int |
| type | int | Tipo di comando per il comportamento dell'effetto di movimento dell'animazione [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array di punti android.graphics.PointF[] |
| ptsType | int | Tipo di punti nel percorso di movimento dell'animazione [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indica se utilizzare coordinate relative o no boolean |
### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti i comandi dalla collezione.
### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

Rimuove i comandi specificati dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Percorso di movimento da rimuovere [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove un comando all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice per rimuovere il comando int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

Restituisce un comando all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento. |

**Restituisce:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Comando all'indice specificato [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)