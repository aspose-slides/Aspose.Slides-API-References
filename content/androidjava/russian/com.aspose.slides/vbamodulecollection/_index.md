---
title: VbaModuleCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию модулей проекта VBA.
type: docs
url: /ru/com.aspose.slides/vbamodulecollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Представляет коллекцию модулей проекта VBA.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает фактическое количество элементов, содержащихся в коллекции. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Удаляет первое вхождение указанного объекта из коллекции. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Добавляет новый пустой модуль в проект VBA. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по элементам коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
### size() {#size--}
```
public final int size()
```


Возвращает фактическое количество элементов, содержащихся в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```


Удаляет первое вхождение указанного объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Модуль, подлежащий удалению из коллекции. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```


Добавляет новый пустой модуль в проект VBA.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя модуля |

**Возвращаемое значение:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Добавленный модуль.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```


Возвращает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```


Возвращает перечислитель, который проходит по элементам коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - java.util.Iterator для всей коллекции.
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

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Возвращает объект синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object