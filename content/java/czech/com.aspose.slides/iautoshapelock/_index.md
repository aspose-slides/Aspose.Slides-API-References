---
title: IAutoShapeLock
second_title: Aspose.Slides pro Java API Reference
description: Určuje, které operace jsou u nadřazeného AutoshapeEx zakázány.
type: docs
url: /cs/com.aspose.slides/iautoshapelock/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IAutoShapeLock extends IBaseShapeLock
```

Určuje, které operace jsou u rodiče AutoshapeEx zakázány.
## Metody

| Metoda | Popis |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Určuje, zda je přidání tohoto tvaru do skupiny zakázáno. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Určuje, zda je přidání tohoto tvaru do skupiny zakázáno. |
| [getSelectLocked()](#getSelectLocked--) | Určuje, zda je výběr tohoto tvaru zakázán. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Určuje, zda je výběr tohoto tvaru zakázán. |
| [getRotateLocked()](#getRotateLocked--) | Určuje, zda je změna úhlu otáčení tohoto tvaru zakázána. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | Určuje, zda je změna úhlu otáčení tohoto tvaru zakázána. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Určuje, zda má tento tvar při změně velikosti zachovat poměr stran. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Určuje, zda má tento tvar při změně velikosti zachovat poměr stran. |
| [getPositionLocked()](#getPositionLocked--) | Určuje, zda je přesunutí tohoto tvaru zakázáno. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | Určuje, zda je přesunutí tohoto tvaru zakázáno. |
| [getSizeLocked()](#getSizeLocked--) | Určuje, zda je změna velikosti tohoto tvaru zakázána. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Určuje, zda je změna velikosti tohoto tvaru zakázána. |
| [getEditPointsLocked()](#getEditPointsLocked--) | Určuje, zda je přímá změna obrysu tohoto tvaru zakázána. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | Určuje, zda je přímá změna obrysu tohoto tvaru zakázána. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | Určuje, zda je změna hodnot úprav zakázána. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | Určuje, zda je změna hodnot úprav zakázána. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | Určuje, zda je změna šipek zakázána. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | Určuje, zda je změna šipek zakázána. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | Určuje, zda je změna typu tvaru zakázána. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | Určuje, zda je změna typu tvaru zakázána. |
| [getTextLocked()](#getTextLocked--) | Určuje, zda je úprava textu zakázána. |
| [setTextLocked(boolean value)](#setTextLocked-boolean-) | Určuje, zda je úprava textu zakázána. |

### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

Určuje, zda je přidání tohoto tvaru do skupiny zakázáno. Boolovská hodnota s možností čtení a zápisu.

**Vrací:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

Určuje, zda je přidání tohoto tvaru do skupiny zakázáno. Boolovská hodnota s možností čtení a zápisu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

Určuje, zda je výběr tohoto tvaru zakázán. Boolovská hodnota s možností čtení a zápisu.

**Vrací:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

Určuje, zda je výběr tohoto tvaru zakázán. Boolovská hodnota s možností čtení a zápisu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

Určuje, zda je změna úhlu otáčení tohoto tvaru zakázána. Boolovská hodnota s možností čtení a zápisu.

**Vrací:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

Určuje, zda je změna úhlu otáčení tohoto tvaru zakázána. Boolovská hodnota s možností čtení a zápisu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

Určuje, zda má tento tvar při změně velikosti zachovat poměr stran. Boolovská hodnota s možností čtení a zápisu.

**Vrací:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

Určuje, zda má tento tvar při změně velikosti zachovat poměr stran. Boolovská hodnota s možností čtení a zápisu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

Určuje, zda je přesunutí tohoto tvaru zakázáno. Boolovská hodnota s možností čtení a zápisu.

**Vrací:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

Určuje, zda je přesunutí tohoto tvaru zakázáno. Boolovská hodnota s možností čtení a zápisu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

Určuje, zda je změna velikosti tohoto tvaru zakázána. Boolovská hodnota s možností čtení a zápisu.

**Vrací:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

Určuje, zda je změna velikosti tohoto tvaru zakázána. Boolovská hodnota s možností čtení a zápisu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

Určuje, zda je přímá změna obrysu tohoto tvaru zakázána. Boolovská hodnota s možností čtení a zápisu.

**Vrací:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

Určuje, zda je přímá změna obrysu tohoto tvaru zakázána. Boolovská hodnota s možností čtení a zápisu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

Určuje, zda je změna hodnot úprav zakázána. Boolovská hodnota s možností čtení a zápisu.

**Vrací:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

Určuje, zda je změna hodnot úprav zakázána. Boolovská hodnota s možností čtení a zápisu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

Určuje, zda je změna šipek zakázána. Boolovská hodnota s možností čtení a zápisu.

**Vrací:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

Určuje, zda je změna šipek zakázána. Boolovská hodnota s možností čtení a zápisu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

Určuje, zda je změna typu tvaru zakázána. Boolovská hodnota s možností čtení a zápisu.

**Vrací:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

Určuje, zda je změna typu tvaru zakázána. Boolovská hodnota s možností čtení a zápisu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTextLocked() {#getTextLocked--}
```
public abstract boolean getTextLocked()
```

Určuje, zda je úprava textu zakázána. Boolovská hodnota s možností čtení a zápisu.

**Vrací:**
boolean
### setTextLocked(boolean value) {#setTextLocked-boolean-}
```
public abstract void setTextLocked(boolean value)
```

Určuje, zda je úprava textu zakázána. Boolovská hodnota s možností čtení a zápisu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |