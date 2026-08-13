---
title: get_Points()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "IInkLine System::Drawing::PointF에 대한 포인트를 가져옵니다. 읽기 전용."
type: docs
weight: 14
url: /ko/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() 메서드


IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) 에 대한 포인트를 가져옵니다. 읽기 전용.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## 비고


예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [InkTrace](../)
* 네임스페이스 [Aspose::Slides::Ink](../../)
* 라이브러리 [Aspose.Slides](../../../)