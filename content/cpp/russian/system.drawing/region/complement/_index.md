---
title: Complement()
second_title: Aspose.Slides для C++ справочник API
description: Заменяет регион, представленный текущим объектом, частью региона, определённого указанным прямоугольником, который не пересекается с этим регионом.
type: docs
weight: 131
url: /ru/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) метод


Заменяет регион, представленный текущим объектом, частью региона, определённого указанным прямоугольником, который не пересекается с этим регионом.

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Прямоугольник, определяющий регион для дополнения |

## Region::Complement(const Rectangle\&) метод


Заменяет регион, представленный текущим объектом, частью региона, определённого указанным прямоугольником, который не пересекается с этим регионом.

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник, определяющий регион для дополнения |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) метод


Заменяет регион, представленный текущим объектом, частью региона, определённого указанным путём, который не пересекается с этим регионом.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Путь, определяющий регион для дополнения |

## Region::Complement(const SharedPtr\<Region\>\&) метод


Заменяет регион, представленный текущим объектом, частью указанного региона, который не пересекается с этим регионом.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Регион для дополнения |

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [RectangleF](../../rectanglef/)
* Класс [Region](../)
* Класс [Rectangle](../../rectangle/)
* Класс [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)