---
title: GetGeometryPaths()
second_title: Aspose.Slides for C++ API 참조
description: 지오메트리 도형의 경로 복사본을 반환합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 합니다.
type: docs
weight: 53
url: /ko/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() 메서드

지오메트리 도형의 경로 복사본을 반환합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```

### 반환값

배열 [IGeometryPath](../../igeometrypath/)

## 비고

예제:
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

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IGeometryPath](../../igeometrypath/)
* 클래스 [GeometryShape](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)