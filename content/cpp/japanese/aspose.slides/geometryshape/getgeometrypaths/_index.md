---
title: GetGeometryPaths()
second_title: Aspose.Slides for C++ API リファレンス
description: ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準とします。
type: docs
weight: 53
url: /ja/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() メソッド


ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準とします。

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### 戻り値

[IGeometryPath](../../igeometrypath/) の配列
## 備考



例: 
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

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IGeometryPath](../../igeometrypath/)
* クラス [GeometryShape](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)