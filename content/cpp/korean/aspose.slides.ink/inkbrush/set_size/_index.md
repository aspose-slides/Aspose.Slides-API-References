---
title: set_Size()
second_title: Aspose.Slides for C++ API 참조
description: 라인의 브러시 크기를 포인트 단위로 설정합니다.
type: docs
weight: 40
url: /ko/aspose.slides.ink/inkbrush/set_size/
---
## InkBrush::set_Size(System::Drawing::SizeF) 메서드


라인의 브러시 크기를 포인트 단위로 설정합니다.

```cpp
void Aspose::Slides::Ink::InkBrush::set_Size(System::Drawing::SizeF value) override
```

## 비고


예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## 참고

* 클래스 [SizeF](../../../system.drawing/sizef/)
* 클래스 [InkBrush](../)
* 네임스페이스 [Aspose::Slides::Ink](../../)
* 라이브러리 [Aspose.Slides](../../../)