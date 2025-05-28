---
title: RawFrame
second_title: Aspose.Sildes для .NET API Справочник
description: Возвращает или задает свойства рамок сырого объекта. Чтение/запись IShapeFrameaspose.slides/ishapeframe.
type: docs
weight: 210
url: /ru/aspose.slides/ishape/rawframe/
---

## Свойство IShape.RawFrame

Возвращает или задает свойства рамки сырого объекта. Чтение/запись [`IShapeFrame`](../../ishapeframe).

```csharp
public IShapeFrame RawFrame { get; set; }
```

### Примеры

Код, который пытается присвоить неопределенную рамку IShape.Frame, не имеет смысла в общем случае (особенно, когда родительский GroupShape многоуровневый внутри других GroupShape). Например:

```csharp
IShape shape = ...;
shape.Frame = new ShapeFrame(float.NaN, float.NaN, float.NaN, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, float.NaN);
```

или

```csharp
slide.Shapes.AddAutoShape(ShapeType.RoundCornerRectangle, float.NaN, float.NaN, float.NaN, float.NaN);
```

Такой код может привести к неясным ситуациям. Поэтому были добавлены ограничения на использование неопределенных значений для IShape.Frame. Значения x, y, width, height, flipH, flipV и rotationAngle должны быть определены (не float.NaN или NullableBool.NotDefined). Пример кода выше теперь вызывает исключение ArgumentException. Это касается следующих случаев использования:

```csharp
IShape shape = ...;
shape.Frame = ...; // не может быть неопределенным

IShapeCollection shapes = ...;
// параметры x, y, width, height не могут быть float.NaN:
{
    shapes.AddAudioFrameCD(...);
    shapes.AddAudioFrameEmbedded(...);
    shapes.AddAudioFrameLinked(...);
    shapes.AddAutoShape(...);
    shapes.AddChart(...);
    shapes.AddConnector(...);
    shapes.AddOleObjectFrame(...);
    shapes.AddPictureFrame(...);
    shapes.AddSmartArt(...);
    shapes.AddTable(...);
    shapes.AddVideoFrame(...);
    shapes.InsertAudioFrameEmbedded(...);
    shapes.InsertAudioFrameLinked(...);
    shapes.InsertAutoShape(...);
    shapes.InsertChart(...);
    shapes.InsertConnector(...);
    shapes.InsertOleObjectFrame(...);
    shapes.InsertPictureFrame(...);
    shapes.InsertTable(...);
    shapes.InsertVideoFrame(...);
}
```

Но свойства рамки IShape.RawFrame могут быть неопределенными. Это имеет смысл, когда объект связан с заполнителем. Тогда неопределенные значения рамки объекта переопределяются значениями родительской рамки заполнителя. Если для этого объекта нет родительской рамки заполнителя, то этот объект использует значения по умолчанию, когда он оценивает эффективную рамку на основе своего IShape.RawFrame. Значения по умолчанию - 0 и NullableBool.False для x, y, width, height, flipH, flipV и rotationAngle. Например:

```csharp
IShape shape = ...; // объект связан с заполнителем
shape.RawFrame = new ShapeFrame(float.NaN, float.NaN, 100, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0); // теперь объект наследует значения x, y, height, flipH, flipV от заполнителя и переопределяет width=100 и rotationAngle=0.
```

### См. Также

* интерфейс [IShapeFrame](../../ishapeframe)
* интерфейс [IShape](../../ishape)
* пространство имен [Aspose.Slides](../../ishape)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->