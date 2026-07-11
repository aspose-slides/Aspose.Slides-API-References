---
title: PointCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию точек анимации.
type: docs
url: /ru/com.aspose.slides/pointcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Представляет коллекцию точек анимации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Возвращает количество точек в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает точку по указанному индексу. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


Возвращает количество точек в коллекции. Только для чтения int.

**Возвращает:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


Возвращает точку по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента. |

**Возвращает:**
[IPoint](../../com.aspose.slides/ipoint) - объект [IPoint](../../com.aspose.slides/ipoint).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Перечислитель, который может использоваться для перебора элементов коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - java.util.Iterator для всей коллекции.