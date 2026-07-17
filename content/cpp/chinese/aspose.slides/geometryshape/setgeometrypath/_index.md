---
title: SetGeometryPath()
second_title: Aspose.Slides C++ API 参考
description: "从 IGeometryPath 对象更新形状几何。坐标必须相对于形状的左上角。将形状的类型 (ShapeType) 更改为 ShapeType::Custom。"
type: docs
weight: 66
url: /zh/aspose.slides/geometryshape/setgeometrypath/
---
## GeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) method

从[IGeometryPath](../../igeometrypath/)对象更新形状几何。坐标必须相对于形状的左上角。将形状的类型 ([ShapeType](../../shapetype/)) 更改为 [ShapeType::Custom](../../shapetype/)。

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | 几何路径 |
## 备注



示例:
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

## 另请参阅

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IGeometryPath](../../igeometrypath/)
* 类 [GeometryShape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)