---
title: ITagCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию тегов, пары строк, определяемые пользователем
type: docs
url: /ru/com.aspose.slides/itagcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Представляет коллекцию тегов (пары строк, определяемые пользователем)
## Методы

| Метод | Описание |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Добавляет новый тег в коллекцию. |
| [remove(String name)](#remove-java.lang.String-) | Удаляет тег с указанным именем из коллекции. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Возвращает нулевой индекс указанного ключа в коллекции. |
| [contains(String name)](#contains-java.lang.String-) | Определяет, содержит ли коллекция конкретное имя. |
| [removeAt(int index)](#removeAt-int-) | Удаляет тег по указанному индексу. |
| [clear()](#clear--) | Удаляет все теги из коллекции. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Возвращает значение тега по указанному индексу. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Возвращает ключ тега по указанному индексу. |
| [getNamesOfTags()](#getNamesOfTags--) | Возвращает имена тегов. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Возвращает или задает пару «ключ-значение» тега. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Возвращает или задает пару «ключ-значение» тега. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Добавляет новый тег в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя тега. |
| value | java.lang.String | Значение тега. |

**Возвращает:**
int - Индекс добавленного тега.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Удаляет тег с указанным именем из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя удаляемого тега. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

Возвращает нулевой индекс указанного ключа в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя для поиска в коллекции. |

**Возвращает:**
int - Нулевой индекс ключа, если ключ найден в коллекции; иначе -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Определяет, содержит ли коллекция конкретное имя.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Ключ для поиска. |

**Возвращает:**
boolean - True, если коллекция содержит тег с указанным ключом; иначе false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет тег по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс тега для удаления. |

### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все теги из коллекции.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Возвращает значение тега по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс тега для возврата. |

**Возвращает:**
java.lang.String - Значение тега.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Возвращает ключ тега по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс тега для возврата. |

**Возвращает:**
java.lang.String - Ключ тега.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Возвращает имена тегов.

**Возвращает:**
java.lang.String[] - Имена тегов.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Возвращает или задает пару «ключ-значение» тега.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Ключ тега. |

**Возвращает:**
java.lang.String - Значение тега.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Возвращает или задает пару «ключ-значение» тега.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Ключ тега. |
| value | java.lang.String |  |