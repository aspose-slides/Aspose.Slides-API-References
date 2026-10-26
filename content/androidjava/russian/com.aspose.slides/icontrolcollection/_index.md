---
title: IControlCollection
second_title: Aspose.Slides для Android через Java API Reference
description: Коллекция элементов управления ActiveX.
type: docs
url: /ru/com.aspose.slides/icontrolcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Коллекция ActiveX элементов управления.
## Методы

| Метод | Описание |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Удаляет элемент управления ActiveX из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент управления ActiveX, хранящийся в указанной позиции, из коллекции. |
| [clear()](#clear--) | Удаляет все элементы управления из коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент управления в указанной позиции. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Создаёт и добавляет новый элемент управления в коллекцию. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Удаляет элемент управления ActiveX из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Элемент управления для удаления. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент управления ActiveX, хранящийся в указанной позиции, из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента управления для удаления. |

### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все элементы управления из коллекции.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Возвращает элемент управления в указанной позиции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента управления. |

**Возвращаемое значение:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Создаёт и добавляет новый элемент управления в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| controlType | int | Тип элемента управления, который следует добавить. |
| x | float | Координата X левой стороны рамки фигуры. |
| y | float | Координата Y верхней стороны рамки фигуры. |
| width | float | Ширина рамки фигуры. |
| height | float | Высота рамки фигуры. |

**Возвращаемое значение:**
[IControl](../../com.aspose.slides/icontrol) - Созданный элемент управления [IControl](../../com.aspose.slides/icontrol).