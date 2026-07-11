---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет 3D вращение диаграммы.
type: docs
url: /ru/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Представляет 3D вращение диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getRotationX()](#getRotationX--) | Возвращает или задаёт степень вращения вокруг оси X, т.е. |
| [setRotationX(byte value)](#setRotationX-byte-) | Возвращает или задаёт степень вращения вокруг оси X, т.е. |
| [getRotationY()](#getRotationY--) | Возвращает или задаёт степень вращения вокруг оси Y, т.е. |
| [setRotationY(int value)](#setRotationY-int-) | Возвращает или задаёт степень вращения вокруг оси Y, т.е. |
| [getPerspective()](#getPerspective--) | Возвращает или задаёт значение перспективы (угол обзора) для 3D диаграмм (от 0 до 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Возвращает или задаёт значение перспективы (угол обзора) для 3D диаграмм (от 0 до 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Определяет, находятся ли оси диаграммы под прямыми углами, а не нарисованы в перспективе. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Определяет, находятся ли оси диаграммы под прямыми углами, а не нарисованы в перспективе. |
| [getDepthPercents()](#getDepthPercents--) | Возвращает или задаёт глубину 3D диаграммы в процентах от ширины диаграммы (от 20 до 2000 процентов). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Возвращает или задаёт глубину 3D диаграммы в процентах от ширины диаграммы (от 20 до 2000 процентов). |
| [getHeightPercents()](#getHeightPercents--) | Указывает высоту 3D диаграммы в процентах от ширины диаграммы (от 5 до 500 процентов). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Указывает высоту 3D диаграммы в процентах от ширины диаграммы (от 5 до 500 процентов). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Возвращает или задаёт степень вращения вокруг оси X, т.е. в направлении Y для 3D диаграмм (от -90 до 90 градусов). Свойство соответствует элементу 21.2.2.157 rotX (X Rotation) в ECMA-376 и параметру "Y Rotation" в PowerPoint 2007+. Чтение/запись byte.

**Возвращаемое значение:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Возвращает или задаёт степень вращения вокруг оси X, т.е. в направлении Y для 3D диаграмм (от -90 до 90 градусов). Свойство соответствует элементу 21.2.157 rotX (X Rotation) в ECMA-376 и параметру "Y Rotation" в PowerPoint 2007+. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Возвращает или задаёт степень вращения вокруг оси Y, т.е. в направлении X для 3D диаграмм (от 0 до 360 градусов). Свойство соответствует элементу 21.2.2.158 rotY (Y Rotation) в ECMA-376 и параметру "X Rotation" в PowerPoint 2007+. Чтение/запись int.

**Возвращаемое значение:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Возвращает или задаёт степень вращения вокруг оси Y, т.е. в направлении X для 3D диаграмм (от 0 до 360 градусов). Свойство соответствует элементу 21.2.2.158 rotY (Y Rotation) в ECMA-376 и параметру "X Rotation" в PowerPoint 2007+. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Возвращает или задаёт значение перспективы (угол обзора) для 3D диаграмм (от 0 до 100). Игнорируется, если значение свойства RightAngleAxes равно true. Чтение/запись byte.

**Возвращаемое значение:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Возвращает или задаёт значение перспективы (угол обзора) для 3D диаграмм (от 0 до 100). Игнорируется, если значение свойства RightAngleAxes равно true. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Определяет, находятся ли оси диаграммы под прямыми углами, а не нарисованы в перспективе. Другими словами, определяет, независимы ли углы осей диаграммы от её вращения или наклона. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Определяет, находятся ли оси диаграммы под прямыми углами, а не нарисованы в перспективе. Другими словами, определяет, независимы ли углы осей диаграммы от её вращения или наклона. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Возвращает или задаёт глубину 3D диаграммы в процентах от ширины диаграммы (от 20 до 2000 процентов). Чтение/запись int.

**Возвращаемое значение:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Возвращает или задаёт глубину 3D диаграммы в процентах от ширины диаграммы (от 20 до 2000 процентов). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Указывает высоту 3D диаграммы в процентах от ширины диаграммы (от 5 до 500 процентов). Чтение/запись int.

**Возвращаемое значение:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Указывает высоту 3D диаграммы в процентах от ширины диаграммы (от 5 до 500 процентов). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |