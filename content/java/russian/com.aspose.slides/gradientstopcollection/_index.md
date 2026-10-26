---
title: GradientStopCollection
second_title: Справочник API Aspose.Slides для Java
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
| [add(float position, Color color)](#add-float-java.awt.Color-) | Создает новую градиентную остановку и добавляет её в конец коллекции. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Создает новую градиентную остановку и добавляет её в конец коллекции. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Создает новую градиентную остановку и добавляет её в конец коллекции. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Создает новую градиентную остановку и вставляет её в указанное место коллекции. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Создает новую градиентную остановку и вставляет её в указанное место коллекции. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Создает новую градиентную остановку и вставляет её в указанное место коллекции. |
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

Версия. Только для чтения long.

**Возвращает:**
long

### size() {#size--}
```
public final int size()
```

Возвращает количество градиентных остановок в коллекции. Только для чтения int.

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

### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```

Создает новую градиентную остановку и добавляет её в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | float | Позиция новой градиентной остановки. |
| color | java.awt.Color | Цвет новой градиентной остановки. |

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

### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```

Создает новую градиентную остановку и вставляет её в указанное место коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс в коллекции, где будет вставлена новая градиентная остановка. |
| position | float | Позиция новой градиентной остановки. |
| color | java.awt.Color | Цвет новой градиентной остановки. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Создает новую градиентную остановку и вставляет её в указанное место коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс в коллекции, где будет вставлена новая градиентная остановка. |
| position | float | Позиция новой градиентной остановки. |
| presetColor | int | Цвет новой градиентной остановки. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Создает новую градиентную остановку и вставляет её в указанное место коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс в коллекции, где будет вставлена новая градиентная остановка. |
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - A IGenericEnumerator, который может использоваться для перебора элементов коллекции.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - An java.util.Iterator, который позволяет перебрать всю коллекцию.

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

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Возвращает:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Возвращает:**
java.lang.Object