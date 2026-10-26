---
title: SetGeometryPaths()
second_title: Aspose.Slides для C++ справочник API
description: "Обновляет геометрию фигуры из массива IGeometryPath. Координаты должны быть относительно левого верхнего угла фигуры. Меняет тип фигуры (ShapeType) на ShapeType::Custom."
type: docs
weight: 79
url: /ru/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) метод


Обновляет геометрию фигуры из массива [IGeometryPath](../../igeometrypath/). Координаты должны быть относительно левого верхнего угла фигуры. Меняет тип фигуры ([ShapeType](../../shapetype/)) на [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Массив путей геометрии |
## Замечания



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

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IGeometryPath](../../igeometrypath/)
* Класс [GeometryShape](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)