---
title: ISmartArtNodeCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию узлов SmartArt.
type: docs
url: /ru/com.aspose.slides/ismartartnodecollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Представляет коллекцию узлов SmartArt.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает узел по индексу. |
| [addNode()](#addNode--) | Добавляет новый узел или дочерний узел. |
| [removeNode(int index)](#removeNode-int-) | Удаляет узел или дочерний узел по индексу. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Удаляет узел или дочерний узел. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Добавляет новый узел в выбранную позицию коллекции узлов. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


Возвращает узел по индексу. Только для чтения [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента. |

**Возвращаемое значение:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


Добавляет новый узел или дочерний узел.

**Возвращаемое значение:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Добавленный узел
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


Удаляет узел или дочерний узел по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс узла |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


Удаляет узел или дочерний узел.

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
| position | int | Позиция узла, начиная с нуля. |

**Возвращаемое значение:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Добавленный узел