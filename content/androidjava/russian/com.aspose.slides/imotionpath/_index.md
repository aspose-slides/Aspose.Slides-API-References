---
title: IMotionPath
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет путь движения.
type: docs
url: /ru/com.aspose.slides/imotionpath/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Представляет путь движения.
## Методы

| Метод | Описание |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Добавить новую команду в путь |
| [getCount()](#getCount--) | Возвращает количество путей в коллекции. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Вставить новую команду в путь |
| [clear()](#clear--) | Удаляет все команды из коллекции. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Удаляет указанные команды из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет команду по указанному индексу. |
| [get_Item(int index)](#get-Item-int-) | Возвращает команду по указанному индексу. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Добавить новую команду в путь

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип команды для поведения анимационного эффекта движения [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Массив точек android.graphics.PointF[] |
| ptsType | int | Тип точек в пути анимационного движения [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Указывает, использовать ли относительные координаты или нет boolean |

**Возвращаемое значение:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Команда пути [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Возвращает количество путей в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Вставить новую команду в путь

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс для вставки команды int |
| type | int | Тип команды для поведения анимационного эффекта движения [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Массив точек android.graphics.PointF[] |
| ptsType | int | Тип точек в пути анимационного движения [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Указывает, использовать ли относительные координаты или нет boolean |

### clear() {#clear--}
```
public abstract void clear()
```


Удаляет все команды из коллекции.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


Удаляет указанные команды из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Путь движения для удаления [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Удаляет команду по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс для удаления команды int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Возвращает команду по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента. |

**Возвращаемое значение:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Команда по указанному индексу [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)