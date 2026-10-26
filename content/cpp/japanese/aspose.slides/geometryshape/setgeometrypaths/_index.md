---
title: SetGeometryPaths()
second_title: Aspose.Slides for C++ API リファレンス
description: "IGeometryPath の配列からシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準にする必要があります。シェイプのタイプ (ShapeType) を ShapeType::Custom に変更します。"
type: docs
weight: 79
url: /ja/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) メソッド

[IGeometryPath](../../igeometrypath/) の配列からシェイプジオメトリを更新します。座標はシェイプの左上隅を基準にする必要があります。シェイプのタイプ ([ShapeType](../../shapetype/)) を [ShapeType::Custom](../../shapetype/) に変更します。

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | ジオメトリパスの配列 |
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

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IGeometryPath](../../igeometrypath/)
* クラス [GeometryShape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)