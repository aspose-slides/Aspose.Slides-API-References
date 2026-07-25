---
title: SetGeometryPath()
second_title: Aspose.Slides for C++ API リファレンス
description: "IGeometryPath オブジェクトから形状ジオメトリを更新します。座標は形状の左上隅を基準とする必要があります。形状のタイプ (ShapeType) を ShapeType::Custom に変更します。"
type: docs
weight: 66
url: /ja/aspose.slides/geometryshape/setgeometrypath/
---
## GeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) メソッド

[IGeometryPath](../../igeometrypath/) オブジェクトから形状ジオメトリを更新します。座標は形状の左上隅を基準とする必要があります。形状のタイプ ([ShapeType](../../shapetype/)) を [ShapeType::Custom](../../shapetype/) に変更します。

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | ジオメトリ パス |

## 備考

例:
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

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IGeometryPath](../../igeometrypath/)
* クラス [GeometryShape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)