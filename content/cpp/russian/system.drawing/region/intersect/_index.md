---
title: Intersect()
second_title: Справочник API Aspose.Slides для C++
description: Заменяет регион, представленный текущим объектом, результатом пересечения этого региона и региона, определённого указанным прямоугольником.
type: docs
weight: 79
url: /ru/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) метод

Заменяет регион, представленный текущим объектом, результатом пересечения этого региона и региона, определенного указанным прямоугольником.

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Прямоугольник, определяющий регион, с которым следует пересечь текущий регион |

## Region::Intersect(const Rectangle\&) метод

Заменяет регион, представленный текущим объектом, результатом пересечения этого региона и региона, определенного указанным прямоугольником.

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник, определяющий регион, с которым следует пересечь текущий регион |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) метод

Заменяет регион, представленный текущим объектом, результатом пересечения этого региона и региона, определенного указанным путем.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Путь, определяющий регион, с которым следует пересечь текущий регион |

## Region::Intersect(const SharedPtr\<Region\>\&) метод

Заменяет регион, представленный текущим объектом, результатом пересечения этого региона и указанного региона.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Регион, с которым следует пересечь текущий регион |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [RectangleF](../../rectanglef/)
* Класс [Region](../)
* Класс [Rectangle](../../rectangle/)
* Класс [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)