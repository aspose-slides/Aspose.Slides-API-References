---
title: SmartArtNodeCollection
second_title: Aspose.Slides для Java справочник API
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
| [size()](#size--) | Возвращает количество узлов в коллекции Только для чтения  int  Только для чтения  int . |
| [addNode()](#addNode--) | Добавить новый узел SmartArt или дочерний узел. |
| [removeNode(int index)](#removeNode-int-) | Удалить узел или дочерний узел по индексу |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Удалить узел или дочерний узел |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Добавить новый узел в выбранной позиции коллекции узлов |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Возвращает узел по индексу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента |

**Возвращаемое значение:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Узел SmartArt
### size() {#size--}
```
public final int size()
```

Возвращает количество узлов в коллекции Только для чтения  int  Только для чтения  int .

**Возвращаемое значение:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Добавить новый узел SmartArt или дочерний узел.

**Возвращаемое значение:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Добавленный узел
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Удалить узел или дочерний узел по индексу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс узла |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Удалить узел или дочерний узел

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Узел для удаления |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Добавить новый узел в выбранной позиции коллекции узлов

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | int | Нулевая позиция узла |

**Возвращаемое значение:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Добавленный узел
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - java.util.Iterator для всей коллекции.
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

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения  boolean .

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object