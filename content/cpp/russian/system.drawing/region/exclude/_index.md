---
title: Exclude()
second_title: Aspose.Slides для C++ Справочник API
description: Заменяет регион, представляемый текущим объектом, результатом исключения из него региона, определённого указанным прямоугольником.
type: docs
weight: 92
url: /ru/system.drawing/region/exclude/
---
## Region::Exclude(const RectangleF\&) метод

Заменяет регион, представляемый текущим объектом, результатом исключения из него региона, определённого указанным прямоугольником.

```cpp
void System::Drawing::Region::Exclude(const RectangleF &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Прямоугольник, определяющий регион для исключения |

## Region::Exclude(const Rectangle\&) метод

Заменяет регион, представляемый текущим объектом, результатом исключения из него региона, определённого указанным прямоугольником.

```cpp
void System::Drawing::Region::Exclude(const Rectangle &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник, определяющий регион для исключения |

## Region::Exclude(const SharedPtr\<Drawing2D::GraphicsPath\>\&) метод

Заменяет регион, представляемый текущим объектом, результатом исключения из него региона, определённого указанным путем.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Путь, определяющий регион для исключения |

## Region::Exclude(const SharedPtr\<Region\>\&) метод

Заменяет регион, представляемый текущим объектом, результатом исключения из него указанного региона.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Region> &region)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Регион для исключения |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [RectangleF](../../rectanglef/)
* Класс [Region](../)
* Класс [Rectangle](../../rectangle/)
* Класс [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Пространство имён [System::Drawing](../../)
* Library [Aspose.Slides](../../../)