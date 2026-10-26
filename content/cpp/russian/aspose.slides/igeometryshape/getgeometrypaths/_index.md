---
title: GetGeometryPaths()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает копию пути геометрической фигуры. Координаты указаны относительно левого верхнего угла фигуры.
type: docs
weight: 53
url: /ru/aspose.slides/igeometryshape/getgeometrypaths/
---
## IGeometryShape::GetGeometryPaths() метод


Возвращает копию пути геометрической фигуры. Координаты заданы относительно левого верхнего угла фигуры.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::IGeometryShape::GetGeometryPaths()=0
```


### Возвращаемое значение

Массив [IGeometryPath](../../igeometrypath/)
## Примечания



Пример: 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>();

auto shape = AsCast<GeometryShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 200.0f, 100.0f));

auto geometryPath = shape->GetGeometryPaths()->idx_get(0);

geometryPath->LineTo(100.0f, 50.0f, 1);
geometryPath->LineTo(100.0f, 50.0f, 4);

shape->SetGeometryPath(geometryPath);

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IGeometryPath](../../igeometrypath/)
* Класс [IGeometryShape](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)