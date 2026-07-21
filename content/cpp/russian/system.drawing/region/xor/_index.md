---
title: Xor()
second_title: Aspose.Slides для C++ справочник API
description: Заменяет регион, представленный текущим объектом, на части этого региона и региона, определённые указанным прямоугольником, которые не пересекаются.
type: docs
weight: 144
url: /ru/system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) метод

Заменяет регион, представленный текущим объектом, на части этого региона и региона, определённые указанным прямоугольником, которые не пересекаются.

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Прямоугольник, определяющий регион для операции xor с регионом, представленным текущим объектом |

## Region::Xor(const Rectangle\&) метод

Заменяет регион, представленный текущим объектом, на части этого региона и региона, определённые указанным прямоугольником, которые не пересекаются.

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник, определяющий регион для операции xor с регионом, представленным текущим объектом |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) метод

Заменяет регион, представленный текущим объектом, на части этого региона и региона, определённые указанным путём, которые не пересекаются.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Путь, определяющий регион для операции xor с регионом, представленным текущим объектом |

## Region::Xor(const SharedPtr\<Region\>\&) метод

Заменяет регион, представленный текущим объектом, на части этого региона и указанного региона, которые не пересекаются.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Регион для операции xor с регионом, представленным текущим объектом |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)