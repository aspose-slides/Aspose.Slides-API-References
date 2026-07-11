---
title: BehaviorPropertyCollection
second_title: Aspose.Slides для Android через Java API
description: Представляет свойства тайминга для поведения эффекта.
type: docs
url: /ru/com.aspose.slides/behaviorpropertycollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Представляет свойства тайминга для поведения эффекта.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество свойств, хранящихся в коллекции. |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Добавляет новое свойство в коллекцию. |
| [add(String propertyValue)](#add-java.lang.String-) | Добавляет новое свойство в коллекцию. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Определяет индекс конкретного элемента в List. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Определяет индекс конкретного элемента по значению свойства в List. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Вставляет новое свойство в коллекцию по указанному индексу. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Вставляет новое свойство (с указанным значением свойства) в коллекцию по указанному индексу. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с определенного индекса массива. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Удаляет указанное свойство из коллекции. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Удаляет указанное свойство из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет свойство по указанному индексу. |
| [clear()](#clear--) | Удаляет все свойства из коллекции. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
| [get_Item(int index)](#get-Item-int-) | Возвращает свойство по указанному индексу. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Устанавливает свойство по указанному индексу. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### size() {#size--}
```
public final int size()
```

Возвращает количество свойств, хранящихся в коллекции. Только для чтения int.

**Возвращает:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Получает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. Только для чтения boolean.

**Возвращает:**
boolean - true, если [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения; иначе false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Добавляет новое свойство в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Свойство для добавления. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Добавляет новое свойство в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyValue | java.lang.String | Значение свойства для добавления. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

Определяет индекс конкретного элемента в List.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Объект для поиска в List. |

**Возвращает:**
int - Индекс элемента, если найден в списке; иначе -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Определяет индекс конкретного элемента по значению свойства в List.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyValue | java.lang.String | значение свойства |

**Возвращает:**
int - Индекс свойства с указанным значением
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Вставляет новое свойство в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс, где должно быть вставлено новое свойство. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Свойство для добавления. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Вставляет новое свойство (с указанным значением свойства) в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс, где должно быть вставлено новое свойство. |
| propertyValue | java.lang.String | Значение свойства для добавления. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с определенного индекса массива.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Одномерный массив, в который копируются элементы из [IGenericCollection](../../com.aspose.slides/igenericcollection). Массив должен иметь нулевую базовую индексацию. |
| arrayIndex | int | Нулевой индекс в массиве, с которого начинается копирование. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Удаляет указанное свойство из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Свойство для удаления. |

**Возвращает:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Удаляет указанное свойство из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyValue | java.lang.String | Значение свойства для удаления. |

**Возвращает:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет свойство по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс свойства, которое должно быть удалено. |

### clear() {#clear--}
```
public final void clear()
```

Удаляет все свойства из коллекции.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Свойство для поиска в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращает:**
boolean - true, если элемент найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyValue | java.lang.String | Значение свойства для поиска в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращает:**
boolean - true, если propertyValue найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Возвращает свойство по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс свойства для возврата. |

**Возвращает:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Свойство поведения анимации.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Устанавливает свойство по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс свойства для возврата. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Возвращает перечислитель, который перебирает коллекцию.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - IGenericEnumerator, который можно использовать для перебора коллекции.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Возвращает:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Возвращает:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Возвращает:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - java.util.Iterator для всей коллекции.