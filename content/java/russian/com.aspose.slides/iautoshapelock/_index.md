---
title: IAutoShapeLock
second_title: Справочник API Aspose.Slides для Java
description: Определяет, какие операции отключены у родительского AutoshapeEx.
type: docs
url: /ru/com.aspose.slides/iautoshapelock/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IAutoShapeLock extends IBaseShapeLock
```

Определяет, какие операции отключены у родительского AutoshapeEx.
## Методы

| Метод | Описание |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Определяет, запрещено ли добавление этой фигуры в группу. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Определяет, запрещено ли добавление этой фигуры в группу. |
| [getSelectLocked()](#getSelectLocked--) | Определяет, запрещено ли выбор этой фигуры. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Определяет, запрещено ли выбор этой фигуры. |
| [getRotateLocked()](#getRotateLocked--) | Определяет, запрещено ли изменение угла вращения этой фигуры. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | Определяет, запрещено ли изменение угла вращения этой фигуры. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Определяет, должна ли фигура сохранять соотношение сторон при изменении размера. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Определяет, должна ли фигура сохранять соотношение сторон при изменении размера. |
| [getPositionLocked()](#getPositionLocked--) | Определяет, запрещено ли перемещение этой фигуры. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | Определяет, запрещено ли перемещение этой фигуры. |
| [getSizeLocked()](#getSizeLocked--) | Определяет, запрещено ли изменение размера этой фигуры. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Определяет, запрещено ли изменение размера этой фигуры. |
| [getEditPointsLocked()](#getEditPointsLocked--) | Определяет, запрещено ли прямое изменение контура этой фигуры. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | Определяет, запрещено ли прямое изменение контура этой фигуры. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | Определяет, запрещено ли изменение параметров регулировки. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | Определяет, запрещено ли изменение параметров регулировки. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | Определяет, запрещено ли изменение стрелочных наконечников. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | Определяет, запрещено ли изменение стрелочных наконечников. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | Определяет, запрещено ли изменение типа фигуры. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | Определяет, запрещено ли изменение типа фигуры. |
| [getTextLocked()](#getTextLocked--) | Определяет, запрещено ли редактирование текста. |
| [setTextLocked(boolean value)](#setTextLocked-boolean-) | Определяет, запрещено ли редактирование текста. |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

Определяет, запрещено ли добавление этой фигуры в группу. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

Определяет, запрещено ли добавление этой фигуры в группу. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

Определяет, запрещено ли выбор этой фигуры. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

Определяет, запрещено ли выбор этой фигуры. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

Определяет, запрещено ли изменение угла вращения этой фигуры. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

Определяет, запрещено ли изменение угла вращения этой фигуры. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

Определяет, должна ли фигура сохранять соотношение сторон при изменении размера. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

Определяет, должна ли фигура сохранять соотношение сторон при изменении размера. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

Определяет, запрещено ли перемещение этой фигуры. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

Определяет, запрещено ли перемещение этой фигуры. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

Определяет, запрещено ли изменение размера этой фигуры. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

Определяет, запрещено ли изменение размера этой фигуры. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

Определяет, запрещено ли прямое изменение контура этой фигуры. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

Определяет, запрещено ли прямое изменение контура этой фигуры. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

Определяет, запрещено ли изменение параметров регулировки. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

Определяет, запрещено ли изменение параметров регулировки. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

Определяет, запрещено ли изменение стрелочных наконечников. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

Определяет, запрещено ли изменение стрелочных наконечников. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

Определяет, запрещено ли изменение типа фигуры. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

Определяет, запрещено ли изменение типа фигуры. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getTextLocked() {#getTextLocked--}
```
public abstract boolean getTextLocked()
```

Определяет, запрещено ли редактирование текста. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setTextLocked(boolean value) {#setTextLocked-boolean-}
```
public abstract void setTextLocked(boolean value)
```

Определяет, запрещено ли редактирование текста. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |