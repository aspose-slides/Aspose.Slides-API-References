---
title: IGeometryShape
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет родительский класс для всех геометрических фигур.
type: docs
weight: 5450
url: /ru/net/aspose.slides/igeometryshape/
---
## IGeometryShape interface

Представляет родительский класс для всех геометрических фигур.

```csharp
public interface IGeometryShape : IShape
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Adjustments](../../aspose.slides/igeometryshape/adjustments) { get; } | Возвращает набор значений настройки формы. Только для чтения[`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AsIShape](../../aspose.slides/igeometryshape/asishape) { get; } | Позволяет получить базовый интерфейс IShape. Только для чтения[`IShape`](../ishape). |
| [ShapeStyle](../../aspose.slides/igeometryshape/shapestyle) { get; } | Возвращает объект стиля фигуры. Только для чтения[`IShapeStyle`](../ishapestyle). |
| [ShapeType](../../aspose.slides/igeometryshape/shapetype) { get; set; } | Возвращает или задает тип предустановки геометрии. Примечание:при изменении значения все значения регулировки будут возвращены к значениям по умолчанию. Чтение/запись[`ShapeType`](../shapetype). |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateShapeElements](../../aspose.slides/igeometryshape/createshapeelements)() | Создает и возвращает массив элементов формы. |
| [GetGeometryPaths](../../aspose.slides/igeometryshape/getgeometrypaths)() | Возвращает копию пути геометрической фигуры. Координаты относятся к левому верхнему углу фигуры. |
| [SetGeometryPath](../../aspose.slides/igeometryshape/setgeometrypath)(IGeometryPath) | Обновляет геометрию формы из объекта[`IGeometryPath`](../igeometrypath). Координаты должны быть относительно левого верхнего угла фигуры. Изменяет тип фигуры ([`ShapeType`](./shapetype)) наCustom. |
| [SetGeometryPaths](../../aspose.slides/igeometryshape/setgeometrypaths)(IGeometryPath[]) | Обновляет геометрию формы из массива[`IGeometryPath`](../igeometrypath). Координаты должны быть относительно левого верхнего угла фигуры. Изменяет тип фигуры ([`ShapeType`](./shapetype)) наCustom. |

### Смотрите также

* interface [IShape](../ishape)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->