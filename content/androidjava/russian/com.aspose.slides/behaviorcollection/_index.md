---
title: BehaviorCollection
second_title: Aspose.Slides для Android через Java API
description: Представляет коллекцию эффектов поведения.
type: docs
url: /ru/com.aspose.slides/behaviorcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Представляет коллекцию эффектов поведения.
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Возвращает количество поведений в коллекции. |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Добавить новое поведение в коллекцию. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Определяет индекс конкретного элемента в списке. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Вставляет новое поведение в коллекцию по указанному индексу. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с определённого индекса массива. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Удаляет указанное поведение из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет поведение из коллекции по указанному индексу. |
| [clear()](#clear--) | Удаляет все поведения из коллекции. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
| [get_Item(int index)](#get-Item-int-) | Возвращает поведение по указанному индексу. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Устанавливает поведение по указанному индексу. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### getCount() {#getCount--}
```
public final int getCount()
```


Возвращает количество поведений в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. Только для чтения boolean.

**Возвращаемое значение:**
boolean – true, если [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения; иначе false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```


Добавить новое поведение в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Поведение для добавления. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```


Определяет индекс конкретного элемента в списке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Объект, который нужно найти в списке. |

**Возвращаемое значение:**
int – индекс элемента, если он найден в списке; иначе -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```


Вставляет новое поведение в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс, по которому должно быть вставлено новое поведение. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Поведение для вставки. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```


Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с определённого индекса массива.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Одномерный массив, который служит получателем скопированных элементов из [IGenericCollection](../../com.aspose.slides/igenericcollection). Массив должен иметь нулевую базу индексации. |
| arrayIndex | int | Нулевой индекс в массиве, с которого начинается копирование. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```


Удаляет указанное поведение из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Поведение для удаления. |

**Возвращаемое значение:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Удаляет поведение из коллекции по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс поведения, которое нужно удалить. |

### clear() {#clear--}
```
public final void clear()
```


Удаляет все поведения из коллекции.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```


Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Объект, который нужно найти в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращаемое значение:**
boolean – true, если элемент найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```


Возвращает поведение по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс поведения, которое нужно вернуть. |

**Возвращаемое значение:**
[IBehavior](../../com.aspose.slides/ibehavior) – анимационное поведение.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```


Устанавливает поведение по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс поведения, которое нужно установить. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```


Возвращает перечислитель, который перебирает коллекцию.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> – IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> – java.util.Iterator для всей коллекции.