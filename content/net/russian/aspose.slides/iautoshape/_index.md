---
title: IAutoShape
second_title: Aspose.Sildes для .NET API Reference
description: Представляет AutoShape.
type: docs
weight: 5040
url: /ru/aspose.slides/iautoshape/
---

## Интерфейс IAutoShape

Представляет AutoShape.

```csharp
public interface IAutoShape : IGeometryShape
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIGeometryShape](../../aspose.slides/iautoshape/asigeometryshape) { get; } | Позволяет получить базовый интерфейс IGeometryShape. Только для чтения [`IGeometryShape`](../igeometryshape). |
| [AutoShapeLock](../../aspose.slides/iautoshape/autoshapelock) { get; } | Возвращает блокировки AutoShape. Только для чтения [`IAutoShapeLock`](../iautoshapelock). |
| [IsTextBox](../../aspose.slides/iautoshape/istextbox) { get; } | Указывает, является ли фигура текстовым полем. |
| [ShapeLock](../../aspose.slides/iautoshape/shapelock) { get; } | Возвращает блокировки формы. Только для чтения [`IAutoShapeLock`](../iautoshapelock). |
| [TextFrame](../../aspose.slides/iautoshape/textframe) { get; } | Возвращает объект TextFrame для AutoShape. Только для чтения [`ITextFrame`](../itextframe). |
| [UseBackgroundFill](../../aspose.slides/iautoshape/usebackgroundfill) { get; set; } | Определяет, следует ли заполнять эту автофигуру фоном слайда вместо указанного по стилю или формату заполнения. Чтение/запись Boolean. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddTextFrame](../../aspose.slides/iautoshape/addtextframe)(string) | Добавляет новый TextFrame к фигуре. Если у фигуры уже есть TextFrame, то просто изменяет его текст. |

### Смотрите также

* интерфейс [IGeometryShape](../igeometryshape)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->