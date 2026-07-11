---
title: ColorOperationCollection
second_title: Справочник API Aspose.Slides для Android через Java
description: Представляет коллекцию операций цветового преобразования.
type: docs
url: /ru/com.aspose.slides/coloroperationcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Представляет коллекцию операций цветового преобразования.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество операций в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает или задаёт операцию по указанному индексу. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Возвращает или задаёт операцию по указанному индексу. |
| [add(int operation, float parameter)](#add-int-float-) | Добавляет новую операцию в конец коллекции. |
| [add(int operation)](#add-int-) | Добавляет новую операцию в конец коллекции. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Вставляет новую операцию в коллекцию. |
| [insert(int position, int operation)](#insert-int-int-) | Вставляет новую операцию в коллекцию. |
| [removeAt(int index)](#removeAt-int-) | Удаляет операцию цвета из коллекции. |
| [clear()](#clear--) | Удаляет все операции цвета. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает корень синхронизации. |
| [deepClone()](#deepClone--) | Создаёт копию коллекции ColorOperationCollection. |
| [cloneT()](#cloneT--) | Клонирует текущий объект |
### size() {#size--}
```
public final int size()
```

Возвращает количество операций в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Возвращает или задаёт операцию по указанному индексу. Чтение/запись [ColorOperation](../../com.aspose.slides/coloroperation).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Возвращает или задаёт операцию по указанному индексу. Чтение/запись [ColorOperation](../../com.aspose.slides/coloroperation).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |
### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Добавляет новую операцию в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operation | int | Тип операции. |
| parameter | float | Параметр операции. |

**Возвращаемое значение:**
[IColorOperation](../../com.aspose.slides/icoloroperation) – добавленная операция.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Добавляет новую операцию в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operation | int | Тип операции. |

**Возвращаемое значение:**
[IColorOperation](../../com.aspose.slides/icoloroperation) – добавленная операция.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Вставляет новую операцию в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | int | Индекс, в который будет вставлена операция. |
| operation | int | Тип операции. |
| parameter | float | Параметр операции. |

**Возвращаемое значение:**
[IColorOperation](../../com.aspose.slides/icoloroperation) – вставленная операция.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Вставляет новую операцию в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | int | Индекс, в который будет вставлена операция. |
| operation | int | Тип операции. |

**Возвращаемое значение:**
[IColorOperation](../../com.aspose.slides/icoloroperation) – вставленная операция.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет операцию цвета из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс операции цвета для удаления. |
### clear() {#clear--}
```
public final void clear()
```

Удаляет все операции цвета.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - java.util.Iterator для всей коллекции.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает корень синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Создаёт копию коллекции ColorOperationCollection.

**Возвращаемое значение:**
java.lang.Object - Новая коллекция [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection).
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Клонирует текущий объект

**Возвращаемое значение:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Клон