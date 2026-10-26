---
title: Union()
second_title: Справочник API Aspose.Slides для C++
description: Заменяет регион, представленный текущим объектом, результатом операции объединения этого региона и региона, определённого указанным прямоугольником.
type: docs
weight: 53
url: /ru/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) метод

Заменяет регион, представленный текущим объектом, результатом операции объединения этого региона и региона, определённого указанным прямоугольником.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Прямоугольник, определяющий регион, с которым объединяется данный регион |
## Region::Union(const Rectangle\&) метод

Заменяет регион, представленный текущим объектом, результатом объединения этого региона и региона, определённого указанным прямоугольником.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник, определяющий регион, с которым объединяется данный регион |
## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) метод

Заменяет регион, представленный текущим объектом, результатом объединения этого региона и региона, определённого указанным путём.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Путь, определяющий регион, с которым объединяется данный регион |
## Region::Union(const SharedPtr\<Region\>\&) метод

Заменяет регион, представленный текущим объектом, результатом объединения этого региона и указанного региона.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Регион, с которым объединяется данный регион |
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)