---
title: IConnectorLock
second_title: Referência da API Aspose.Slides para Java
description: Determina quais operações estão desativadas no Conector pai.
type: docs
url: /pt/com.aspose.slides/iconnectorlock/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IConnectorLock extends IBaseShapeLock
```

Determina quais operações estão desativadas no Conector pai.

## Métodos

| Método | Descrição |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Determina se a adição desta forma a um grupo é proibida. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Determina se a adição desta forma a um grupo é proibida. |
| [getSelectLocked()](#getSelectLocked--) | Determina se a seleção desta forma é proibida. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Determina se a seleção desta forma é proibida. |
| [getRotateLocked()](#getRotateLocked--) | Determina se a alteração do ângulo de rotação desta forma é proibida. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | Determina se a alteração do ângulo de rotação desta forma é proibida. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Determina se uma forma deve preservar a proporção ao redimensionar. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Determina se uma forma deve preservar a proporção ao redimensionar. |
| [getPositionMove()](#getPositionMove--) | Determina se o movimento desta forma é proibido. |
| [setPositionMove(boolean value)](#setPositionMove-boolean-) | Determina se o movimento desta forma é proibido. |
| [getSizeLocked()](#getSizeLocked--) | Determina se o redimensionamento desta forma é proibido. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Determina se o redimensionamento desta forma é proibido. |
| [getEditPointsLocked()](#getEditPointsLocked--) | Determina se a alteração direta do contorno desta forma é proibida. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | Determina se a alteração direta do contorno desta forma é proibida. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | Determina se a alteração dos valores de ajuste é proibida. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | Determina se a alteração dos valores de ajuste é proibida. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | Determina se a alteração das pontas de seta é proibida. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | Determina se a alteração das pontas de seta é proibida. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | Determina se a alteração do tipo de forma é proibida. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | Determina se a alteração do tipo de forma é proibida. |

### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

Determina se a adição desta forma a um grupo é proibida. Leitura/gravação boolean.

**Retorna:**
boolean

### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

Determina se a adição desta forma a um grupo é proibida. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

Determina se a seleção desta forma é proibida. Leitura/gravação boolean.

**Retorna:**
boolean

### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

Determina se a seleção desta forma é proibida. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

Determina se a alteração do ângulo de rotação desta forma é proibida. Leitura/gravação boolean.

**Retorna:**
boolean

### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

Determina se a alteração do ângulo de rotação desta forma é proibida. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

Determina se uma forma deve preservar a proporção ao redimensionar. Leitura/gravação boolean.

**Retorna:**
boolean

### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

Determina se uma forma deve preservar a proporção ao redimensionar. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getPositionMove() {#getPositionMove--}
```
public abstract boolean getPositionMove()
```

Determina se o movimento desta forma é proibido. Leitura/gravação boolean.

**Retorna:**
boolean

### setPositionMove(boolean value) {#setPositionMove-boolean-}
```
public abstract void setPositionMove(boolean value)
```

Determina se o movimento desta forma é proibido. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

Determina se o redimensionamento desta forma é proibido. Leitura/gravação boolean.

**Retorna:**
boolean

### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

Determina se o redimensionamento desta forma é proibido. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

Determina se a alteração direta do contorno desta forma é proibida. Leitura/gravação boolean.

**Retorna:**
boolean

### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

Determina se a alteração direta do contorno desta forma é proibida. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

Determina se a alteração dos valores de ajuste é proibida. Leitura/gravação boolean.

**Retorna:**
boolean

### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

Determina se a alteração dos valores de ajuste é proibida. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

Determina se a alteração das pontas de seta é proibida. Leitura/gravação boolean.

**Retorna:**
boolean

### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

Determina se a alteração das pontas de seta é proibida. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

Determina se a alteração do tipo de forma é proibida. Leitura/gravação boolean.

**Retorna:**
boolean

### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

Determina se a alteração do tipo de forma é proibida. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |