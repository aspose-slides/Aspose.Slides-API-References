---
title: IGroupShape
second_title: Справочник API Aspose.Slides для Java
description: Представляет группу фигур на слайде.
type: docs
url: /ru/com.aspose.slides/igroupshape/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGroupShape extends IShape
```

Представляет группу фигур на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getGroupShapeLock()](#getGroupShapeLock--) | Возвращает блокировки shape. |
| [getShapes()](#getShapes--) | Возвращает коллекцию фигур внутри группы. |
### getGroupShapeLock() {#getGroupShapeLock--}
```
public abstract IGroupShapeLock getGroupShapeLock()
```

Возвращает блокировки shape. Только для чтения [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Возвращаемое значение:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

Возвращает коллекцию фигур внутри группы. Только для чтения [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Возвращаемое значение:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)