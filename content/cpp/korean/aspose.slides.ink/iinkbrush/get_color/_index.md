---
title: get_Color()
second_title: Aspose.Slides for C++ API 참조
description: 선에 대한 브러시 색상을 가져옵니다.
type: docs
weight: 1
url: /ko/aspose.slides.ink/iinkbrush/get_color/
---
## IInkBrush::get_Color() 메서드


선에 대한 브러시 색상을 가져옵니다.

```cpp
virtual System::Drawing::Color Aspose::Slides::Ink::IInkBrush::get_Color()=0
```

## 비고


예제: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## 참조

* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [IInkBrush](../)
* 네임스페이스 [Aspose::Slides::Ink](../../)
* 라이브러리 [Aspose.Slides](../../../)