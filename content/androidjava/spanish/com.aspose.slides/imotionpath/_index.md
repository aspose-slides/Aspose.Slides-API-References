---
title: IMotionPath
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa la ruta de movimiento.
type: docs
url: /es/com.aspose.slides/imotionpath/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Representa la ruta de movimiento.
## Métodos

| Método | Descripción |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Agregar nuevo comando a la ruta |
| [getCount()](#getCount--) | Devuelve el número de rutas en la colección. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Insertar nuevo comando a la ruta |
| [clear()](#clear--) | Elimina todos los comandos de la colección. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Elimina los comandos especificados de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina un comando en el índice especificado. |
| [get_Item(int index)](#get-Item-int-) | Devuelve un comando en el índice especificado. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Agregar nuevo comando a la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Tipo de comando para el comportamiento del efecto de movimiento de animación [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Matriz de puntos android.graphics.PointF[] |
| ptsType | int | Tipo de puntos en la ruta de movimiento de animación [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indica si se utilizan coordenadas relativas o no boolean |

**Devuelve:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Comando de una ruta [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Devuelve el número de rutas en la colección. Solo lectura int.

**Devuelve:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Insertar nuevo comando a la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice para la inserción del comando int |
| type | int | Tipo de comando para el comportamiento del efecto de movimiento de animación [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Matriz de puntos android.graphics.PointF[] |
| ptsType | int | Tipo de puntos en la ruta de movimiento de animación [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indica si se utilizan coordenadas relativas o no boolean |
### clear() {#clear--}
```
public abstract void clear()
```


Elimina todos los comandos de la colección.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


Elimina los comandos especificados de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Ruta de movimiento a eliminar [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Elimina un comando en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice para eliminar el comando int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Devuelve un comando en el índice especificado.

**Parámetro:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento. |

**Devuelve:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Comando en el índice especificado [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)