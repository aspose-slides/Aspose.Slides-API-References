---
title: PortionCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию частей.
type: docs
url: /ru/com.aspose.slides/portioncollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Представляет коллекцию частей.
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Получает количество элементов, фактически содержащихся в коллекции. |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Получает элемент по указанному индексу. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Добавляет Portion в конец коллекции. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Определяет индекс конкретного элемента в List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Вставляет Portion в коллекцию по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с указанного индекса массива. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Удаляет первое вхождение конкретного объекта из [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### getCount() {#getCount--}
```
public final int getCount()
```


Получает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. Только для чтения boolean.

**Возвращаемое значение:**
boolean - true если [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения; иначе false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```


Получает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```


Получает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```


Добавляет Portion в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion, который будет добавлен в конец коллекции. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```


Определяет индекс конкретного элемента в List.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Объект, который нужно найти в List. |

**Возвращаемое значение:**
int - Индекс элемента, если он найден в списке; иначе -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```


Вставляет Portion в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому следует вставить Portion. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion для вставки. |

### clear() {#clear--}
```
public final void clear()
```


Удаляет все элементы из коллекции.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```


Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Объект, который нужно найти в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращаемое значение:**
boolean - true если элемент найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```


Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с указанного индекса массива.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Одномерный массив, в который копируются элементы из [IGenericCollection](../../com.aspose.slides/igenericcollection). Массив должен иметь нулевую базовую индексацию. |
| arrayIndex | int | Нулевой индекс в массиве, с которого начинается копирование. |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```


Удаляет первое вхождение конкретного объекта из [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Объект, который нужно удалить из [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращаемое значение:**
boolean - true если объект был успешно удалён из [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false. Этот метод также возвращает false, если объект не найден в исходном [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Удаляет элемент по указанному индексу коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который следует удалить. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```


Возвращает перечислитель, который проходит по коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - IGenericEnumerator, который можно использовать для итерации по коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - java.util.Iterator для всей коллекции.