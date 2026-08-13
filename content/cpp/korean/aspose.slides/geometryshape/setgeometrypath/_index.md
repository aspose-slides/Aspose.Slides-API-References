---
title: SetGeometryPath()
second_title: Aspose.Slides C++ API 레퍼런스
description: "IGeometryPath 객체에서 모양 기하학을 업데이트합니다. 좌표는 모양의 왼쪽 상단 모서리를 기준으로 상대적이어야 합니다. 모양의 유형(ShapeType)을 ShapeType::Custom으로 변경합니다."
type: docs
weight: 66
url: /ko/aspose.slides/geometryshape/setgeometrypath/
---
## GeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) 메서드

[IGeometryPath](../../igeometrypath/) 객체에서 모양 기하학을 업데이트합니다. 좌표는 모양의 왼쪽 상단 모서리를 기준으로 상대적이어야 합니다. 모양의 유형 ([ShapeType](../../shapetype/))을 [ShapeType::Custom](../../shapetype/) 로 변경합니다.

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | 기하학 경로 |

## 비고



예제:
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

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IGeometryPath](../../igeometrypath/)
* 클래스 [GeometryShape](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)