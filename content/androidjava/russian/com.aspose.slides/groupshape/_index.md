---
title: GroupShape
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет группу фигур на слайде.
type: docs
url: /ru/com.aspose.slides/groupshape/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Все реализованные интерфейсы:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Представляет группу фигур на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Возвращает объект LineFormat, содержащий свойства форматирования линии для фигуры. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Возвращает блокировки фигуры. |
| [getShapes()](#getShapes--) | Возвращает коллекцию фигур внутри группы. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Возвращает объект LineFormat, содержащий свойства форматирования линии для фигуры. Примечание: Возвращает null для объектов GroupShape, потому что у них нет свойств линии. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращаемое значение:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


Возвращает блокировки фигуры. Только для чтения [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Возвращаемое значение:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Возвращает коллекцию фигур внутри группы. Только для чтения [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Возвращаемое значение:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)