---
title: FontSubstRuleCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию замен шрифтов.
type: docs
url: /ru/com.aspose.slides/fontsubstrulecollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

Представляет коллекцию замен шрифтов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество элементов, фактически содержащихся в коллекции. |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | Добавляет новое правило замены шрифта в коллекцию |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | Удаляет первое вхождение указанного объекта из коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```

### size() {#size--}
```
public final int size()
```

Возвращает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возвращает:**
int
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```

Добавляет новое правило замены шрифта в коллекцию

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```

Удаляет первое вхождение указанного объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Правило замены шрифта, которое необходимо удалить из коллекции. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```

Возвращает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - IGenericEnumerator, который можно использовать для перебора элементов коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - java.util.Iterator для всей коллекции.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). Только для чтения boolean.

**Возвращает:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Возвращает:**
java.lang.Object