---
title: IMotionPath
second_title: Referencia de la API de Aspose.Slides para Java
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
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Add new command to path |
| [getCount()](#getCount--) | Returns the number of paths in the collection. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Insert new command to path |
| [clear()](#clear--) | Removes all commands from the collection. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Removes specified commans from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a command at the specified index. |
| [get_Item(int index)](#get-Item-int-) | Returns a command at the specified index. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Agregar nuevo comando a la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Tipo de comando para el comportamiento del efecto de movimiento de animación [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Matriz de puntos java.awt.geom.Point2D.Float[] |
| ptsType | int | Tipo de puntos en la ruta de movimiento de animación [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indica si se usan coordenadas relativas o no boolean |

**Devuelve:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Comando de una ruta [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Devuelve el número de rutas en la colección. Solo lectura int.

**Devuelve:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Insertar nuevo comando a la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice para la inserción del comando int |
| type | int | Tipo de comando para el comportamiento del efecto de movimiento de animación [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Matriz de puntos java.awt.geom.Point2D.Float[] |
| ptsType | int | Tipo de puntos en la ruta de movimiento de animación [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indica si se usan coordenadas relativas o no boolean |
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