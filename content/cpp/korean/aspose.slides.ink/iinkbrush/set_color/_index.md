---
title: set_Color()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 라인의 브러시 색상을 설정합니다.
type: docs
weight: 14
url: /ko/aspose.slides.ink/iinkbrush/set_color/
---
## IInkBrush::set_Color(System::Drawing::Color) 메서드

라인의 브러시 색상을 설정합니다.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Color(System::Drawing::Color value)=0
```

## 비고

예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## 참고

* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [IInkBrush](../)
* 네임스페이스 [Aspose::Slides::Ink](../../)
* 라이브러리 [Aspose.Slides](../../../)