---
title: SequenceCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию интерактивных последовательностей.
type: docs
url: /ru/com.aspose.slides/sequencecollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Представляет коллекцию интерактивных последовательностей.
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Возвращает количество элементов в коллекции. Только для чтения int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Добавить новую интерактивную последовательность. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Удаляет указанную последовательность из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет последовательность по указанному индексу. |
| [clear()](#clear--) | Удаляет все последовательности из коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает последовательность по указанному индексу. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### getCount() {#getCount--}
```
public final int getCount()
```

Возвращает количество элементов в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

Добавляет новую интерактивную последовательность. Чтение/запись [Sequence](../../com.aspose.slides/sequence).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Возвращаемое значение:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

Удаляет указанную последовательность из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Последовательность для удаления. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет последовательность по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс последовательности, которую следует удалить. |
### clear() {#clear--}
```
public final void clear()
```

Удаляет все последовательности из коллекции.
### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

Возвращает последовательность по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента. |

**Возвращаемое значение:**
[ISequence](../../com.aspose.slides/isequence) - Объект [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - IGenericEnumerator, который можно использовать для прохода по коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - java.util.Iterator для всей коллекции.