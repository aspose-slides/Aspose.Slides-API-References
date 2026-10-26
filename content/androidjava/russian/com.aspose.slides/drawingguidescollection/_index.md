---
title: DrawingGuidesCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию регулируемых направляющих рисунка.
type: docs
url: /ru/com.aspose.slides/drawingguidescollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Представляет коллекцию регулируемых направляющих рисунка.
## Методы

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает направляющую рисунка по индексу. |
| [add(byte orientation, float position)](#add-byte-float-) | Добавляет направляющую рисунка в конец коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет направляющую рисунка по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [getCount()](#getCount--) | Возвращает количество элементов в коллекции. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Копирует все элементы из коллекции в указанный массив. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


Возвращает направляющую рисунка по индексу. Только для чтения [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


Добавляет направляющую рисунка в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| orientation | byte | Ориентация направляющей рисунка. |
| position | float | Позиция направляющей рисунка в пунктах. |

**Возвращаемое значение:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Удаляет направляющую рисунка по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс направляющей рисунка, которую следует удалить. |

### clear() {#clear--}
```
public final void clear()
```


Удаляет все элементы из коллекции.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - IGenericEnumerator, который можно использовать для перебора элементов коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - java.util.Iterator для всей коллекции.
### getCount() {#getCount--}
```
public final int getCount()
```


Возвращает количество элементов в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |