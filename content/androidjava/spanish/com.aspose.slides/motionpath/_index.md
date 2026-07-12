---
title: MotionPath
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa la ruta de movimiento.
type: docs
url: /es/com.aspose.slides/motionpath/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Representa la ruta de movimiento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Agrega un nuevo comando a la ruta |
| [getCount()](#getCount--) | Returns the number of paths in the collection. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Inserta un nuevo comando a la ruta |
| [clear()](#clear--) | Elimina todos los comandos de la colección. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Elimina los comandos especificados de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina un comando en el índice especificado. |
| [get_Item(int index)](#get-Item-int-) | Devuelve un comando en el índice especificado. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Agrega un nuevo comando a la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Matriz de puntos |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Booleano de coordenadas relativas |

**Devuelve:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Devuelve el número de rutas en la colección. Solo lectura int.

**Devuelve:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Inserta un nuevo comando a la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde se debe insertar el elemento. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Matriz de puntos |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Booleano de coordenadas relativas |

### clear() {#clear--}
```
public final void clear()
```


Elimina todos los comandos de la colección.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Elimina los comandos especificados de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Ruta de movimiento a eliminar. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina un comando en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del comando que debe eliminarse. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Devuelve un comando en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento. |

**Devuelve:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - El objeto [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Un IGenericEnumerator que puede usarse para recorrer la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Un java.util.Iterator para toda la colección.