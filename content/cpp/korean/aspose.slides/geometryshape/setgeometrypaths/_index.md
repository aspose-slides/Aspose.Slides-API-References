---
title: SetGeometryPaths()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "IGeometryPath 배열에서 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 위 모서리를 기준으로 상대적이어야 합니다. 도형의 유형(ShapeType)을 ShapeType::Custom으로 변경합니다."
type: docs
weight: 79
url: /ko/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) 메서드


[IGeometryPath](../../igeometrypath/) 배열에서 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 상대적이어야 합니다. 도형의 유형([ShapeType](../../shapetype/))을 [ShapeType::Custom](../../shapetype/)(으)로 변경합니다.

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```


### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | 배열 기하학 경로 |
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

## 참고

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IGeometryPath](../../igeometrypath/)
* 클래스 [GeometryShape](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)