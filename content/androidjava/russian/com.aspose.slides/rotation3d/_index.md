---
title: Rotation3D
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет 3D-вращение диаграммы.
type: docs
url: /ru/com.aspose.slides/rotation3d/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Представляет 3D-вращение диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getRotationX()](#getRotationX--) | Возвращает или задаёт угол вращения вокруг оси X, т.е. |
| [setRotationX(byte value)](#setRotationX-byte-) | Возвращает или задаёт угол вращения вокруг оси X, т.е. |
| [getRotationY()](#getRotationY--) | Возвращает или задаёт угол вращения вокруг оси Y, т.е. |
| [setRotationY(int value)](#setRotationY-int-) | Возвращает или задаёт угол вращения вокруг оси Y, т.е. |
| [getPerspective()](#getPerspective--) | Возвращает или задаёт значение перспективы (угол поля зрения) для 3-мерных диаграмм (от 0 до 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Возвращает или задаёт значение перспективы (угол поля зрения) для 3-мерных диаграмм (от 0 до 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Определяет, являются ли оси диаграммы прямыми, а не нарисованными в перспективе. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Определяет, являются ли оси диаграммы прямыми, а не нарисованными в перспективе. |
| [getDepthPercents()](#getDepthPercents--) | Возвращает или задаёт глубину 3-мерной диаграммы в процентах от ширины диаграммы (от 20 до 2000 процентов). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Возвращает или задаёт глубину 3-мерной диаграммы в процентах от ширины диаграммы (от 20 до 2000 процентов). |
| [getHeightPercents()](#getHeightPercents--) | Указывает высоту 3-D-диаграммы в процентах от ширины диаграммы (от 5 до 500 процентов). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Указывает высоту 3-D-диаграммы в процентах от ширины диаграммы (от 5 до 500 процентов). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

Возвращает или задаёт угол вращения вокруг оси X, т.е. в направлении Y для 3-мерных диаграмм (от -90 до 90 градусов). Свойство соответствует элементу 21.2.2.157 rotX (X Rotation) в ECMA-376 и опции «Y Rotation» в PowerPoint 2007+. Чтение/запись byte.

**Возвращаемое значение:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

Возвращает или задаёт угол вращения вокруг оси X, т.е. в направлении Y для 3-мерных диаграмм (от -90 до 90 градусов). Свойство соответствует элементу 21.2.2.157 rotX (X Rotation) в ECMA-376 и опции «Y Rotation» в PowerPoint 2007+. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Возвращает или задаёт угол вращения вокруг оси Y, т.е. в направлении X для 3-мерных диаграмм (от 0 до 360 градусов). Свойство соответствует элементу 21.2.2.158 rotY (Y Rotation) в ECMA-376 и опции «X Rotation» в PowerPoint 2007+. Чтение/запись int.

**Возвращаемое значение:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Возвращает или задаёт угол вращения вокруг оси Y, т.е. в направлении X для 3-мерных диаграмм (от 0 до 360 градусов). Свойство соответствует элементу 21.2.2.158 rotY (Y Rotation) в ECMA-376 и опции «X Rotation» в PowerPoint 2007+. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

Возвращает или задаёт значение перспективы (угол поля зрения) для 3-мерных диаграмм (от 0 до 240). Игнорируется, если свойство RightAngleAxes равно true. Чтение/запись byte.

**Возвращаемое значение:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

Возвращает или задаёт значение перспективы (угол поля зрения) для 3-мерных диаграмм (от 0 до 240). Игнорируется, если свойство RightAngleAxes равно true. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Определяет, являются ли оси диаграммы прямыми, а не нарисованными в перспективе. Другими словами, определяет, независимы ли углы осей диаграммы от её вращения или наклона. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Определяет, являются ли оси диаграммы прямыми, а не нарисованными в перспективе. Другими словами, определяет, независимы ли углы осей диаграммы от её вращения или наклона. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

Возвращает или задаёт глубину 3-мерной диаграммы в процентах от ширины диаграммы (от 20 до 2000 процентов). Чтение/запись int.

**Возвращаемое значение:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

Возвращает или задаёт глубину 3-мерной диаграммы в процентах от ширины диаграммы (от 20 до 2000 процентов). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

Указывает высоту 3-D-диаграммы в процентах от ширины диаграммы (от 5 до 500 процентов). Чтение/запись int.

**Возвращаемое значение:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

Указывает высоту 3-D-диаграммы в процентах от ширины диаграммы (от 5 до 500 процентов). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject