---
title: SetGeometryPaths()
second_title: Aspose.Slides for C++ API 參考
description: "從 IGeometryPath 陣列更新形狀幾何。座標必須相對於形狀的左上角。將形狀的類型 (ShapeType) 更改為 ShapeType::Custom."
type: docs
weight: 79
url: /zh-hant/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) 方法

從 [IGeometryPath](../../igeometrypath/) 陣列更新形狀幾何。座標必須相對於形狀的左上角。將形狀的類型 ([ShapeType](../../shapetype/)) 更改為 [ShapeType::Custom](../../shapetype/)。

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | 陣列幾何路徑 |

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

## 另請參閱

* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IGeometryPath](../../igeometrypath/)
* 類別 [IGeometryShape](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)