---
title: Region()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый экземпляр класса Region.
type: docs
weight: 1
url: /ru/system.drawing/region/region/
---
## Region::Region() конструктор

Создает новый экземпляр класса [Region](../).

```cpp
System::Drawing::Region::Region()
```

## Region::Region(const RectangleF\&) конструктор

Создает новый экземпляр класса [Region](../), который представляет область, определённую указанным прямоугольником.

```cpp
System::Drawing::Region::Region(const RectangleF &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Прямоугольник, определяющий область |

## Region::Region(const Rectangle\&) конструктор

Создает новый экземпляр класса [Region](../), который представляет область, определённую указанным прямоугольником.

```cpp
System::Drawing::Region::Region(const Rectangle &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник, определяющий область |

## Region::Region(const SharedPtr\<Drawing2D::GraphicsPath\>\&) конструктор

Создает новый экземпляр класса [Region](../), который представляет область, определённую указанным путём.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Путь, определяющий область |

## Region::Region(const SkPath\&) конструктор

```cpp
System::Drawing::Region::Region(const SkPath &path)
```

## Region::Region(const SharedPtr\<Drawing2D::RegionData\>\&) конструктор

Создает новый экземпляр класса [Region](../), который представляет область, определённую указанным объектом RegionData.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::RegionData> &region_data)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| region_data | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::RegionData](../../../system.drawing.drawing2d/regiondata/)\>\& | Объект RegionData, определяющий область |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Region](../)
* Класс [RectangleF](../../rectanglef/)
* Класс [Rectangle](../../rectangle/)
* Класс [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Класс [RegionData](../../../system.drawing.drawing2d/regiondata/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)