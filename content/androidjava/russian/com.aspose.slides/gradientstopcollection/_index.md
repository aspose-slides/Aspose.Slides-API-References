---
title: GradientStopCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию градиентных остановок.
type: docs
url: /ru/com.aspose.slides/gradientstopcollection/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Представляет коллекцию градиентных остановок.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Возвращает количество градиентных остановок в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает градиентную остановку по индексу. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Создает новую градиентную остановку и добавляет её в конец коллекции. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Создает новую градиентную остановку и добавляет её в конец коллекции. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Создает новую градиентную остановку и добавляет её в конец коллекции. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Создает новую градиентную остановку и вставляет её в указанную позицию в коллекцию. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Создает новую градиентную остановку и вставляет её в указанную позицию в коллекцию. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Создает новую градиентную остановку и вставляет её в указанную позицию в коллекцию. |
| [removeAt(int index)](#removeAt-int-) | Удаляет градиентную остановку по указанному индексу. |
| [clear()](#clear--) | Удаляет все градиентные остановки из коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения, long.

**Возвращает:**
long
### size() {#size--}
```
public final int size()
```

Возвращает количество градиентных остановок в коллекции. Только для чтения, int .

**Возвращает:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

Возвращает градиентную остановку по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

Создает новую градиентную остановку и добавляет её в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | float | Позиция новой градиентной остановки. |
| color | java.lang.Integer | Цвет новой градиентной остановки. |

**Возвращает:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Индекс новой градиентной остановки в коллекции.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

Создает новую градиентную остановку и добавляет её в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | float | Позиция новой градиентной остановки. |
| presetColor | int | Цвет новой градиентной остановки. |

**Возвращает:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Индекс новой градиентной остановки в коллекции.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

Создает новую градиентную остановку и добавляет её в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | float | Позиция новой градиентной остановки. |
| schemeColor | int | Цвет новой градиентной остановки. |

**Возвращает:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Индекс новой градиентной остановки в коллекции.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

Создает новую градиентную остановку и вставляет её в указанную позицию в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс в коллекции, в который будет вставлена новая градиентная остановка. |
| position | float | Позиция новой градиентной остановки. |
| color | java.lang.Integer | Цвет новой градиентной остановки. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Создает новую градиентную остановку и вставляет её в указанную позицию в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс в коллекции, в который будет вставлена новая градиентная остановка. |
| position | float | Позиция новой градиентной остановки. |
| presetColor | int | Цвет новой градиентной остановки. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Создает новую градиентную остановку и вставляет её в указанную позицию в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс в коллекции, в который будет вставлена новая градиентная остановка. |
| position | float | Позиция новой градиентной остановки. |
| schemeColor | int | Цвет новой градиентной остановки. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет градиентную остановку по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс градиентной остановки, которую следует удалить. |
### clear() {#clear--}
```
public final void clear()
```

Удаляет все градиентные остановки из коллекции.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - IGenericEnumerator, который можно использовать для перебора элементов коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - java.util.Iterator для всей коллекции.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения, boolean .

**Возвращает:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения, Object.

**Возвращает:**
java.lang.Object