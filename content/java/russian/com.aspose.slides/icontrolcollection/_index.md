---
title: IControlCollection
second_title: Справочник API Aspose.Slides для Java
description: Коллекция элементов ActiveX.
type: docs
url: /ru/com.aspose.slides/icontrolcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Коллекция элементов ActiveX.
## Методы

| Метод | Описание |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Удаляет элемент ActiveX из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент ActiveX, хранящийся в указанной позиции, из коллекции. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент в указанной позиции. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Создает и добавляет новый элемент в коллекцию. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Удаляет элемент ActiveX из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Элемент для удаления. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент ActiveX, хранящийся в указанной позиции, из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента для удаления. |

### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все элементы из коллекции.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Возвращает элемент в указанной позиции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента. |

**Возвращаемое значение:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Создает и добавляет новый элемент в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| controlType | int | Тип элемента для добавления. |
| x | float | Координата X левой стороны рамки фигуры. |
| y | float | Координата Y верхней стороны рамки фигуры. |
| width | float | Ширина рамки фигуры. |
| height | float | Высота рамки фигуры. |

**Возвращаемое значение:**
[IControl](../../com.aspose.slides/icontrol) - Созданный элемент [IControl](../../com.aspose.slides/icontrol).