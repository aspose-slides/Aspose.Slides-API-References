---
title: ISequenceCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию интерактивных последовательностей.
type: docs
url: /ru/com.aspose.slides/isequencecollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Представляет коллекцию интерактивных последовательностей.
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Возвращает количество элементов в коллекции Только для чтения int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Добавляет новую интерактивную последовательность. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Удаляет указанную последовательность из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет последовательность по указанному индексу. |
| [clear()](#clear--) | Удаляет все последовательности из коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает последовательность по указанному индексу. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Возвращает количество элементов в коллекции Только для чтения int.

**Возвращаемое значение:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

Добавляет новую интерактивную последовательность.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Объект Shape [IShape](../../com.aspose.slides/ishape) |

**Возвращаемое значение:**
[ISequence](../../com.aspose.slides/isequence) - Новая последовательность [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

Удаляет указанную последовательность из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Последовательность для удаления. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет последовательность по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента в коллекции int |

### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все последовательности из коллекции.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

Возвращает последовательность по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента. |

**Возвращаемое значение:**
[ISequence](../../com.aspose.slides/isequence) - Объект [ISequence](../../com.aspose.slides/isequence)