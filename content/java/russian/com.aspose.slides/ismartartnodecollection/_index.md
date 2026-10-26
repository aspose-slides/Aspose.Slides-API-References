---
title: ISmartArtNodeCollection
second_title: Aspose.Slides для Java справка API
description: Представляет собой коллекцию узлов SmartArt.
type: docs
url: /ru/com.aspose.slides/ismartartnodecollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Представляет собой коллекцию узлов SmartArt.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает узел по индексу. |
| [addNode()](#addNode--) | Добавляет новый узел или подузел. |
| [removeNode(int index)](#removeNode-int-) | Удаляет узел или подузел по индексу. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Удаляет узел или подузел. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Добавляет новый узел в выбранную позицию коллекции узлов. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


Возвращает узел по индексу. Только для чтения [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой (от нуля) индекс элемента. |

**Возвращаемое значение:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


Добавляет новый узел или подузел.

**Возвращаемое значение:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Добавленный узел
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


Удаляет узел или подузел по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой (от нуля) индекс узла |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


Удаляет узел или подузел.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Узел для удаления. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


Добавляет новый узел в выбранную позицию коллекции узлов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | int | Нулевой (от нуля) позиция узла. |

**Возвращаемое значение:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Добавленный узел