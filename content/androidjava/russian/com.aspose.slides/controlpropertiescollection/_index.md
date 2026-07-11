---
title: ControlPropertiesCollection
second_title: Aspose.Slides для Android через справочник API Java
description: Коллекция свойств AcitveX.
type: docs
url: /ru/com.aspose.slides/controlpropertiescollection/
---
**Наследование:**  
java.lang.Object

**Все реализованные интерфейсы:**  
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)  
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Коллекция свойств AcitveX.

## Методы

| Метод | Описание |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Добавляет свойство в коллекцию. |
| [remove(String name)](#remove-java.lang.String-) | Удаляет свойство с указанным именем. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Возвращает или задает свойство. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Возвращает или задает свойство. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Возвращает коллекцию имен свойств. |
| [clear()](#clear--) | Удаляет все свойства. |
| [getCount()](#getCount--) | Возвращает количество свойств в коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Добавляет свойство в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства. |
| value | java.lang.String | Значение свойства. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Удаляет свойство с указанным именем.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства для удаления. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
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
public final void set_Item(String name, String value)
```

Возвращает или задает свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Возвращает коллекцию имен свойств. Только для чтения [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Возвращаемое значение:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public final void clear()
```

Удаляет все свойства.

### getCount() {#getCount--}
```
public final int getCount()
```

Возвращает количество свойств в коллекции. Только для чтения int.

**Возвращаемое значение:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.