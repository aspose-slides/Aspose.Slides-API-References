---
title: SetGeometryPaths()
second_title: Aspose.Slides for C++ API 参考
description: "从 IGeometryPath 数组更新形状几何。坐标必须相对于形状的左上角。将形状的类型 (ShapeType) 更改为 ShapeType::Custom."
type: docs
weight: 79
url: /zh/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) 方法

从 [IGeometryPath](../../igeometrypath/) 数组更新形状几何。坐标必须相对于形状的左上角。将形状的类型 ([ShapeType](../../shapetype/)) 更改为 [ShapeType::Custom](../../shapetype/)。

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | 数组几何路径 |
## 备注



示例：
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

## 参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IGeometryPath](../../igeometrypath/)
* 类 [GeometryShape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)