---
title: VbaModuleCollection
second_title: Справочник API Aspose.Slides для Java
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

| Методы | Описание |
| --- | --- |
| [size()](#size--) | Получает количество элементов, фактически содержащихся в коллекции. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Удаляет первое вхождение определённого объекта из коллекции. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Добавляет новый пустой модуль в проект VBA. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
### size() {#size--}
```
public final int size()
```


Получает количество элементов, фактически содержащихся в коллекции. Толькочтение int.

**Возвращает:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```


Удаляет первое вхождение определённого объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Модуль, который необходимо удалить из коллекции. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```


Добавляет новый пустой модуль в проект VBA.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя модуля |

**Возвращает:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Добавленный модуль.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```


Получает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```


Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Перечислитель IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращает:**
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


Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Толькочтение boolean.

**Возвращает:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Возвращает объект синхронизации. Толькочтение Object.

**Возвращает:**
java.lang.Object