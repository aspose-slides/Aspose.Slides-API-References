---
title: IConnectorLock
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Determina qué operaciones están deshabilitadas en el conector padre.
type: docs
url: /es/com.aspose.slides/iconnectorlock/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IConnectorLock extends IBaseShapeLock
```

Determina qué operaciones están deshabilitadas en el conector padre.
## Métodos

| Método | Descripción |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Determines whether an adding this shape to a group is forbidden. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Determines whether an adding this shape to a group is forbidden. |
| [getSelectLocked()](#getSelectLocked--) | Determines whether a selecting this shape is forbidden. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Determines whether a selecting this shape is forbidden. |
| [getRotateLocked()](#getRotateLocked--) | Determines whether a changing rotation angle of this shape is forbidden. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | Determines whether a changing rotation angle of this shape is forbidden. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Determines whether a shape have to preserve aspect ratio on resizing. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Determines whether a shape have to preserve aspect ratio on resizing. |
| [getPositionMove()](#getPositionMove--) | Determines whether a moving this shape is forbidden. |
| [setPositionMove(boolean value)](#setPositionMove-boolean-) | Determines whether a moving this shape is forbidden. |
| [getSizeLocked()](#getSizeLocked--) | Determines whether a resizing this shape is forbidden. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Determines whether a resizing this shape is forbidden. |
| [getEditPointsLocked()](#getEditPointsLocked--) | Determines whether a direct changing of contour of this shape is forbidden. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | Determines whether a direct changing of contour of this shape is forbidden. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | Determines whether a changing adjust values is forbidden. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | Determines whether a changing adjust values is forbidden. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | Determines whether a changing arrowheads is forbidden. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | Determines whether a changing arrowheads is forbidden. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | Determines whether a changing of a shape type is forbidden. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | Determines whether a changing of a shape type is forbidden. |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

Determina si añadir esta shape a un group está prohibido. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

Determina si añadir esta shape a un group está prohibido. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

Determina si seleccionar esta shape está prohibido. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

Determina si seleccionar esta shape está prohibido. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

Determina si cambiar el ángulo de rotación de esta shape está prohibido. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

Determina si cambiar el ángulo de rotación de esta shape está prohibido. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

Determina si la shape debe conservar la proporción al redimensionarse. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

Determina si la shape debe conservar la proporción al redimensionarse. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getPositionMove() {#getPositionMove--}
```
public abstract boolean getPositionMove()
```

Determina si mover esta shape está prohibido. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setPositionMove(boolean value) {#setPositionMove-boolean-}
```
public abstract void setPositionMove(boolean value)
```

Determina si mover esta shape está prohibido. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

Determina si redimensionar esta shape está prohibido. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

Determina si redimensionar esta shape está prohibido. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

Determina si el cambio directo del contorno de esta shape está prohibido. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

Determina si el cambio directo del contorno de esta shape está prohibido. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

Determina si cambiar valores de ajuste está prohibido. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

Determina si cambiar valores de ajuste está prohibido. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

Determina si cambiar cabezas de flecha está prohibido. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

Determina si cambiar cabezas de flecha está prohibido. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

Determina si cambiar el tipo de una shape está prohibido. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

Determina si cambiar el tipo de una shape está prohibido. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |