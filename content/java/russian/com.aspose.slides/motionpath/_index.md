---
title: MotionPath
second_title: Справочник API Aspose.Slides для Java
description: Представляет путь движения.
type: docs
url: /ru/com.aspose.slides/motionpath/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Представляет путь движения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Добавляет новую команду в путь |
| [getCount()](#getCount--) | Возвращает количество путей в коллекции. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Вставляет новую команду в путь |
| [clear()](#clear--) | Удаляет все команды из коллекции. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Удаляет указанные команды из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет команду по указанному индексу. |
| [get_Item(int index)](#get-Item-int-) | Возвращает команду по указанному индексу. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Добавляет новую команду в путь

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Массив точек |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Логическое значение относительных координат |

**Возвращаемое значение:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Возвращает количество путей в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Вставляет новую команду в путь

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому следует вставить элемент. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Массив точек |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Логическое значение относительных координат |

### clear() {#clear--}
```
public final void clear()
```


Удаляет все команды из коллекции.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Удаляет указанные команды из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Путь движения для удаления. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Удаляет команду по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс команды, которую следует удалить. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Возвращает команду по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента. |

**Возвращаемое значение:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Объект [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Возвращает перечислитель, который проходит по коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - IGenericEnumerator, который можно использовать для прохода по коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - java.util.Iterator для всей коллекции.