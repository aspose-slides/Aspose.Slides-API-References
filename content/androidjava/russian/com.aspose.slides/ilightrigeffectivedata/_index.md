---
title: ILightRigEffectiveData
second_title: Aspose.Slides для Android через справочник Java API
description: Неизменяемый объект, содержащий свойства эффективной системы освещения.
type: docs
url: /ru/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Неизменяемый объект, содержащий свойства эффективной системы освещения.

--------------------

Этот интерфейс используется как часть [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getDirection()](#getDirection--) | Направление света. |
| [getLightType()](#getLightType--) | Представляет предустановленное освещение, которое может быть применено к фигуре. |
| [getRotation()](#getRotation--) | Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси как координат широты и долготы. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Направление света. Только для чтения [LightingDirection](../../com.aspose.slides/lightingdirection).

**Возвращает:**
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Представляет предустановленное освещение, которое может быть применено к фигуре. Система освещения представляет собой группу светильников, ориентированных определённым способом относительно 3D-сцены. Только для чтения [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Возвращает:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Вращение определяется использованием координаты широты, координаты долготы и оборота вокруг оси как координат широты и долготы. Первый элемент в возвращаемом массиве — широта, второй — долгота, третий — оборот.

**Возвращает:**
float[] — координаты вращения в виде float[]