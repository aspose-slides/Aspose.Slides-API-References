---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет свойства тайминга для поведения эффекта.
type: docs
url: /ru/com.aspose.slides/ibehaviorpropertycollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Представляет свойства тайминга для поведения эффекта.
## Методы

| Метод | Описание |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Добавляет новое свойство в коллекцию. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Определяет индекс конкретного элемента по значению свойства в списке. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Вставляет новое свойство (с указанным значением свойства) в коллекцию по заданному индексу. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Удаляет указанное свойство из коллекции. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```


Добавляет новое свойство в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyValue | java.lang.String | Значение свойства для добавления. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```


Определяет индекс конкретного элемента по значению свойства в списке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyValue | java.lang.String | значение свойства |

**Возвращаемое значение:**
int - Индекс свойства с указанным значением
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```


Вставляет новое свойство (с указанным значением свойства) в коллекцию по заданному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс, по которому должно быть вставлено новое свойство. |
| propertyValue | java.lang.String | Значение свойства для добавления. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```


Удаляет указанное свойство из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyValue | java.lang.String | Значение свойства для удаления. |

**Возвращаемое значение:**
boolean - true, если свойство успешно удалено
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```


Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyValue | java.lang.String | Значение свойства для поиска в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращаемое значение:**
boolean - true, если propertyValue найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false.