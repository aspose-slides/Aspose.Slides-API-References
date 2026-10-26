---
title: GraphicsPath()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый экземпляр класса GraphicsPath с указанным режимом заливки.
type: docs
weight: 1
url: /ru/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) конструктор

Создает новый экземпляр класса [GraphicsPath](../) с указанным режимом заливки.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Указывает, как следует заполнять внутреннюю часть замкнутого пути, представленного создаваемым объектом |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) конструктор

Создает новый экземпляр объекта [GraphicsPath](../), представляющего указанный путь.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Массив, содержащий точки, задающие путь, который будет представлять создаваемый объект |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий значения, указывающие типы соответствующих точек в массиве **pts** |
| fillMode | [FillMode](../../fillmode/) | Указывает, как следует заполнять внутреннюю часть замкнутого пути, представленного создаваемым объектом |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) конструктор

Создает новый экземпляр объекта [GraphicsPath](../), представляющего указанный путь.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Массив, содержащий точки, задающие путь, который будет представлять создаваемый объект |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий значения, указывающие типы соответствующих точек в массиве **pts** |
| fillMode | [FillMode](../../fillmode/) | Указывает, как следует заполнять внутреннюю часть замкнутого пути, представленного создаваемым объектом |

## GraphicsPath::GraphicsPath(const SkPath\&) конструктор

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## См. также

* Перечисление [FillMode](../../fillmode/)
* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [GraphicsPath](../)
* Класс [Point](../../../system.drawing/point/)
* Класс [PointF](../../../system.drawing/pointf/)
* Пространство имён [System::Drawing::Drawing2D](../../)
* Библиотека [Aspose.Slides](../../../)