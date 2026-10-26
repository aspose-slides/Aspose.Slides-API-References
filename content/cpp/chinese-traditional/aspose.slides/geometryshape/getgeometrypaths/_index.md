---
title: GetGeometryPaths()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回幾何形狀路徑的副本。座標相對於形狀的左上角。
type: docs
weight: 53
url: /zh-hant/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() 方法


返回幾何形狀路徑的副本。座標相對於形狀的左上角。

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### 返回值

陣列 [IGeometryPath](../../igeometrypath/)
## 備註



範例：
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

## 參見

* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IGeometryPath](../../igeometrypath/)
* 類別 [GeometryShape](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)