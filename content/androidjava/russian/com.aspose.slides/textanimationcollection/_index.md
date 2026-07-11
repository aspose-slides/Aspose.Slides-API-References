---
title: TextAnimationCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию текстовых анимаций.
type: docs
url: /ru/com.aspose.slides/textanimationcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

Представляет коллекцию текстовых анимаций.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество элементов в коллекции. |
| [add()](#add--) | Добавляет новую текстовую анимацию в коллекцию. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по индексу. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Возвращает все элементы |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```


Возвращает количество элементов в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### add() {#add--}
```
public final TextAnimation add()
```


Добавляет новую текстовую анимацию в коллекцию.

**Возвращаемое значение:**
[TextAnimation](../../com.aspose.slides/textanimation) - Добавлен [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```


Возвращает элемент по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```


Возвращает все элементы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) для удаления. |

**Возвращаемое значение:**
com.aspose.slides.ITextAnimation[] - Массив [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```


Возвращает перечислитель, который перебирает коллекцию.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - java.util.Iterator для всей коллекции.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Массив для заполнения. |
| index | int | Начальная позиция в целевом массиве. |

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


Возвращает объект синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object