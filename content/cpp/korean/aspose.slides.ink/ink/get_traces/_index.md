---
title: get_Traces()
second_title: Aspose.Slides for C++ API 레퍼런스
description: IInk 요소 IInkTrace에 포함된 모든 트레이스를 가져옵니다. 읽기 전용.
type: docs
weight: 1
url: /ko/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() 메서드


[IInk](../../iink/) 요소 [IInkTrace](../../iinktrace/)에 포함된 모든 트레이스를 가져옵니다. 읽기 전용.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## 비고


예제: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IInkTrace](../../iinktrace/)
* 클래스 [Ink](../)
* 네임스페이스 [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)