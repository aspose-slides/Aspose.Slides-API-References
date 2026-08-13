---
title: get_Brush()
second_title: Aspose.Slides for C++ API 참조
description: IInkLine에 대한 Brush를 가져옵니다. IInkBrush는 읽기 전용입니다.
type: docs
weight: 1
url: /ko/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() 메서드

IInkLine [IInkBrush](../../iinkbrush/)에 대한 Brush를 가져옵니다. 읽기 전용.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## 비고

예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IInkBrush](../../iinkbrush/)
* 클래스 [IInkTrace](../)
* 네임스페이스 [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)