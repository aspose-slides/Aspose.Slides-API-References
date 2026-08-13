---
title: SetGeometryPaths()
second_title: Aspose.Slides for C++ API 참조
description: "배열 IGeometryPath에서 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 위 모서리를 기준으로 상대적이어야 합니다. 도형의 유형(ShapeType)을 ShapeType::Custom으로 변경합니다."
type: docs
weight: 79
url: /ko/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) method

배열 [IGeometryPath](../../igeometrypath/)에서 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 위 모서리를 기준으로 상대적이어야 합니다. 도형의 유형([ShapeType](../../shapetype/))을 [ShapeType::Custom](../../shapetype/)로 변경합니다.

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | 배열 기하 경로 |

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

## 또한 보기

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IGeometryPath](../../igeometrypath/)
* 클래스 [IGeometryShape](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)