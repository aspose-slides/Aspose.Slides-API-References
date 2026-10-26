---
title: IControlPropertiesCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Коллекция элементов управления ActiveX.
type: docs
url: /ru/com.aspose.slides/icontrolpropertiescollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Коллекция элементов управления ActiveX.
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Возвращает количество свойств в коллекции. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Добавляет свойство в коллекцию. |
| [remove(String name)](#remove-java.lang.String-) | Удаляет свойство с указанным именем. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Возвращает или задает свойство. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Возвращает или задает свойство. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Возвращает количество свойств в коллекции. |
| [clear()](#clear--) | Удаляет все свойства. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Возвращает количество свойств в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


Добавляет свойство в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства. |
| value | java.lang.String | Значение свойства. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Удаляет свойство с указанным именем.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства для удаления. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Возвращает или задает свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства. |

**Возвращаемое значение:**
java.lang.String - Свойство.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Возвращает или задает свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Возвращает количество свойств в коллекции. Только для чтения [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Возвращаемое значение:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


Удаляет все свойства.