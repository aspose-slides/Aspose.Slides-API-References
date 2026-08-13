---
title: GetGeometryPaths()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지오메트리 도형의 경로 복사본을 반환합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 합니다.
type: docs
weight: 53
url: /ko/aspose.slides/igeometryshape/getgeometrypaths/
---
## IGeometryShape::GetGeometryPaths() 메서드


지오메트리 도형의 경로 복사본을 반환합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::IGeometryShape::GetGeometryPaths()=0
```


### 반환 값

배열 [IGeometryPath](../../igeometrypath/)
## 비고



예시: 
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

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IGeometryPath](../../igeometrypath/)
* 클래스 [IGeometryShape](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)