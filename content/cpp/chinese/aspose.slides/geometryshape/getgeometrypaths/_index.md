---
title: GetGeometryPaths()
second_title: Aspose.Slides C++ API 参考
description: 返回几何形状路径的副本。坐标相对于形状的左上角。
type: docs
weight: 53
url: /zh/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() 方法

返回几何形状路径的副本。坐标相对于形状的左上角。

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```

### 返回值

[IGeometryPath](../../igeometrypath/) 的数组
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

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IGeometryPath](../../igeometrypath/)
* 类 [GeometryShape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)