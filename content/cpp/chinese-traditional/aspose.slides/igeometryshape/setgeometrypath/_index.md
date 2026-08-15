---
title: SetGeometryPath()
second_title: Aspose.Slides for C++ API 參考
description: "從 IGeometryPath 物件更新形狀幾何。座標必須相對於形狀的左上角。將形狀的類型 (ShapeType) 更改為 ShapeType::Custom。"
type: docs
weight: 66
url: /zh-hant/aspose.slides/igeometryshape/setgeometrypath/
---
## IGeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) method

從 [IGeometryPath](../../igeometrypath/) 物件更新形狀幾何。座標必須相對於形狀的左上角。將形狀的類型 ([ShapeType](../../shapetype/)) 更改為 [ShapeType::Custom](../../shapetype/)。

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | 幾何路徑 |
## 備註

範例：
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

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IGeometryPath](../../igeometrypath/)
* 類別 [IGeometryShape](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)