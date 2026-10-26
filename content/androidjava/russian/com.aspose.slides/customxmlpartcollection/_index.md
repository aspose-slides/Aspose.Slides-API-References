---
title: CustomXmlPartCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию пользовательских XML-частей.
type: docs
url: /ru/com.aspose.slides/customxmlpartcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Представляет коллекцию пользовательских XML-частей.

## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [size()](#size--) | Возвращает количество пользовательских XML-частей в коллекции. |
| [add(String xmlString)](#add-java.lang.String-) | Добавляет новую пользовательскую XML-часть. |
| [add(byte[] xmlData)](#add-byte---) | Добавляет новую пользовательскую XML-часть. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Добавляет новую пользовательскую XML-часть. |
| [removeAt(int index)](#removeAt-int-) | Удаляет пользовательскую XML-часть по указанному индексу. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Удаляет первое вхождение указанного объекта из коллекции. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Возвращает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой (отсчёт с нуля) индекс элемента, который нужно получить. |

**Возвращаемое значение:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Элемент по указанному индексу.

### size() {#size--}
```
public final int size()
```

Возвращает количество пользовательских XML-частей в коллекции. Только для чтения int.

**Возвращаемое значение:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Добавляет новую пользовательскую XML-часть.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlString | java.lang.String | XML-строка новой части, которую нужно добавить. |

**Возвращаемое значение:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Созданная пользовательская XML-часть.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Добавляет новую пользовательскую XML-часть.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlData | byte[] | XML-данные новой части, которые нужно добавить. |

**Возвращаемое значение:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Созданная пользовательская XML-часть.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Добавляет новую пользовательскую XML-часть.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток ввода с XML-данными новой части, которую нужно добавить. |

**Возвращаемое значение:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Созданная пользовательская XML-часть.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет пользовательскую XML-часть по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой (отсчёт с нуля) индекс элемента, который нужно удалить. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Удаляет первое вхождение указанного объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Пользовательскую XML-часть, которую нужно удалить. |

**Возвращаемое значение:**
boolean - true, если элемент успешно удалён; иначе false.

### clear() {#clear--}
```
public final void clear()
```

Удаляет все элементы из коллекции.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Массив, в который следует скопировать. |
| index | int | Индекс, с которого начинается копирование. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Возвращаемое значение:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - An java.util.Iterator for the entire collection.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject