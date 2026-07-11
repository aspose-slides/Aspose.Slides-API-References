---
title: ControlCollection
second_title: Aspose.Slides для Android через Java API Reference
description: Коллекция элементов управления ActiveX.
type: docs
url: /ru/com.aspose.slides/controlcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Коллекция элементов управления ActiveX.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество объектов в коллекции. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Создаёт и добавляет новый элемент управления в коллекцию. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Удаляет элемент управления ActiveX из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент управления ActiveX, хранящийся в указанной позиции, из коллекции. |
| [clear()](#clear--) | Удаляет все элементы управления из коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент управления в указанной позиции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует всю коллекцию в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает корень синхронизации. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Возвращает количество объектов в коллекции. Только для чтения int.

**Возвращает:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Создаёт и добавляет новый элемент управления в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| controlType | int | Тип добавляемого элемента управления. |
| x | float | Координата X левой стороны рамки фигуры. |
| y | float | Координата Y верхней стороны рамки фигуры. |
| width | float | Ширина рамки фигуры. |
| height | float | Высота рамки фигуры. |

**Возвращает:**
[IControl](../../com.aspose.slides/icontrol) - Созданный элемент управления.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Удаляет элемент управления ActiveX из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Элемент управления для удаления. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент управления ActiveX, хранящийся в указанной позиции, из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента управления для удаления. |

### clear() {#clear--}
```
public final void clear()
```

Удаляет все элементы управления из коллекции.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Возвращает элемент управления в указанной позиции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента управления. |

**Возвращает:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Перечислитель IGenericEnumerator, который можно использовать для прохода по коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - java.util.Iterator для всей коллекции.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует всю коллекцию в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив |
| index | int | Индекс в целевом массиве. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Возвращает:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает корень синхронизации. Только для чтения Object.

**Возвращает:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject