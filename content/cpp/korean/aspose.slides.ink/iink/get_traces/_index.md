---
title: get_Traces()
second_title: Aspose.Slides C++ API 레퍼런스
description: IInk 요소 IInkTrace에 포함된 모든 트레이스를 가져옵니다. 읽기 전용.
type: docs
weight: 1
url: /ko/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() 메서드

[IInk](../) 요소 [IInkTrace](../../iinktrace/)에 포함된 모든 트레이스를 가져옵니다. 읽기 전용.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## 비고

예시:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IInkTrace](../../iinktrace/)
* 클래스 [IInk](../)
* 네임스페이스 [Aspose::Slides::Ink](../../)
* 라이브러리 [Aspose.Slides](../../../)