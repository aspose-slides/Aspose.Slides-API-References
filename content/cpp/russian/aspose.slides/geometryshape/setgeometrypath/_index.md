---
title: SetGeometryPath()
second_title: Aspose.Slides для C++ справочник API
description: "Обновляет геометрию фигуры из объекта IGeometryPath. Координаты должны быть относительно левого верхнего угла фигуры. Меняет тип фигуры (ShapeType) на ShapeType::Custom."
type: docs
weight: 66
url: /ru/aspose.slides/geometryshape/setgeometrypath/
---
## GeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) метод

Обновляет геометрию фигуры из объекта [IGeometryPath](../../igeometrypath/). Координаты должны быть относительно левого верхнего угла фигуры. Меняет тип фигуры ([ShapeType](../../shapetype/)) на [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | Геометрический путь |
## Примечания

Пример:
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>();

auto shape = AsCast<GeometryShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 200.0f, 100.0f));

auto geometryPath0 = MakeObject<GeometryPath>();
geometryPath0->MoveTo(0.0f, 0.0f);
geometryPath0->LineTo(shape->get_Width(), 0.0f);
geometryPath0->LineTo(shape->get_Width(), shape->get_Height() / 3);
geometryPath0->LineTo(0.0f, shape->get_Height() / 3);
geometryPath0->CloseFigure();

auto geometryPath1 = MakeObject<GeometryPath>();
geometryPath1->MoveTo(0.0f, shape->get_Height() / 3 * 2);
geometryPath1->LineTo(shape->get_Width(), shape->get_Height() / 3 * 2);
geometryPath1->LineTo(shape->get_Width(), shape->get_Height());
geometryPath1->LineTo(0.0f, shape->get_Height());
geometryPath1->CloseFigure();

shape->SetGeometryPaths(StaticCastArray<SharedPtr<IGeometryPath>>(MakeArray<SharedPtr<GeometryPath>>({geometryPath0, geometryPath1})));

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IGeometryPath](../../igeometrypath/)
* Класс [GeometryShape](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)