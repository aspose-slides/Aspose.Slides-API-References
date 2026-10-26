---
title: SmartArtNodeCollection
second_title: Aspose.Slides для Android через справку по Java API
description: Представляет коллекцию узлов SmartArt.
type: docs
url: /ru/com.aspose.slides/smartartnodecollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Представляет коллекцию узлов SmartArt.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает узел по индексу |
| [size()](#size--) | Возвращает количество узлов в коллекции. Только для чтения int. |
| [addNode()](#addNode--) | Добавляет новый узел SmartArt или дочерний узел. |
| [removeNode(int index)](#removeNode-int-) | Удаляет узел или дочерний узел по индексу |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Удаляет узел или дочерний узел |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Добавляет новый узел в выбранной позиции коллекции узлов |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Возвращает узел по индексу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Узел SmartArt
### size() {#size--}
```
public final int size()
```

Возвращает количество узлов в коллекции. Только для чтения int.

**Returns:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Добавляет новый узел SmartArt или дочерний узел.

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Добавленный узел
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Удаляет узел или дочерний узел по индексу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс узла |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Удаляет узел или дочерний узел

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Узел для удаления |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Добавляет новый узел в выбранной позиции коллекции узлов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | int | Нулевая позиция узла |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Добавленный узел
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Возвращает перечислитель, который перебирает коллекцию.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Перечислитель IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - java.util.Iterator для всей коллекции.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы из коллекции в указанный массив.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Returns:**
java.lang.Object