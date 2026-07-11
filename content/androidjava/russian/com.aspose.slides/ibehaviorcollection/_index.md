---
title: IBehaviorCollection
second_title: Справочник API Aspose.Slides для Android на Java
description: Представляет коллекцию эффектов поведения.
type: docs
url: /ru/com.aspose.slides/ibehaviorcollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Представляет коллекцию эффектов поведения.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает поведение по указанному индексу. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Возвращает поведение по указанному индексу. |
| [getCount()](#getCount--) | Возвращает количество поведений в коллекции. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Добавляет новое поведение в коллекцию. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Определяет индекс конкретного элемента в List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Вставляет новое поведение в коллекцию по указанному индексу. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Удаляет указанное поведение из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет поведение из коллекции по указанному индексу. |
| [clear()](#clear--) | Удаляет все поведения из коллекции. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```


Возвращает поведение по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс поведения, которое нужно вернуть. |

**Возвращаемое значение:**
[IBehavior](../../com.aspose.slides/ibehavior) - Анимационное поведение.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```


Возвращает поведение по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс поведения, которое нужно вернуть. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Возвращает количество поведений в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```


Добавляет новое поведение в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Поведение для добавления. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```


Определяет индекс конкретного элемента в List.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Объект, который нужно найти в List. |

**Возвращаемое значение:**
int - Индекс элемента, если он найден в списке; иначе -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```


Вставляет новое поведение в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс, куда должно быть вставлено новое поведение. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Поведение для вставки. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```


Удаляет указанное поведение из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Поведение для удаления. |

**Возвращаемое значение:**
boolean - true если поведение успешно удалено boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Удаляет поведение из коллекции по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс поведения, которое нужно удалить. |

### clear() {#clear--}
```
public abstract void clear()
```


Удаляет все поведения из коллекции.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```


Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Объект, который нужно найти в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращаемое значение:**
boolean - true если элемент найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false.