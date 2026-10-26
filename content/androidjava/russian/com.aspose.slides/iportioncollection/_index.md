---
title: IPortionCollection
second_title: Aspose.Slides для Android через справку Java API
description: Представляет коллекцию частей.
type: docs
url: /ru/com.aspose.slides/iportioncollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Представляет коллекцию частей.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [getCount()](#getCount--) | Возвращает количество элементов, фактически содержащихся в коллекции. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Добавляет Portion в конец коллекции. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Определяет индекс конкретной части в коллекции. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Вставляет Portion в коллекцию по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Удаляет первое вхождение конкретного объекта из [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


Возвращает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Возвращает количество элементов, фактически содержащихся в коллекции. Толькo для чтения int.

**Возвращаемое значение:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


Добавляет Portion в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion, который будет добавлен в конец коллекции. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


Определяет индекс конкретной части в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Часть, которую нужно найти в коллекции. |

**Возвращаемое значение:**
int — индекс элемента, если он найден в коллекции; иначе -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


Вставляет Portion в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевая индексная позиция, по которой следует вставить Portion. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion для вставки. |

### clear() {#clear--}
```
public abstract void clear()
```


Удаляет все элементы из коллекции.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```


Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Объект, который нужно найти в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращаемое значение:**
boolean — true, если элемент найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


Удаляет первое вхождение конкретного объекта из [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Объект, который нужно удалить из [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращаемое значение:**
boolean — true, если элемент был успешно удалён из [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false. Этот метод также возвращает false, если элемент не найден в исходном [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Удаляет элемент по указанному индексу из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевая индексная позиция элемента, который необходимо удалить. |
