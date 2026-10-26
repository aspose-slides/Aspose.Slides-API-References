---
title: set_Color()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: กำหนดสีของแปรงสำหรับเส้น.
type: docs
weight: 14
url: /th/aspose.slides.ink/iinkbrush/set_color/
---
## IInkBrush::set_Color(System::Drawing::Color) เมธอด

กำหนดสีของแปรงสำหรับเส้น.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Color(System::Drawing::Color value)=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## ดูเพิ่มเติม

* คลาส [Color](../../../system.drawing/color/)
* คลาส [IInkBrush](../)
* เนมสเปส [Aspose::Slides::Ink](../../)
* ไลบรารี [Aspose.Slides](../../../)