---
title: get_Color()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: รับค่าสีของแปรงสำหรับเส้น.
type: docs
weight: 1
url: /th/aspose.slides.ink/iinkbrush/get_color/
---
## IInkBrush::get_Color() วิธีการ


รับค่าสีของแปรงสำหรับเส้น.

```cpp
virtual System::Drawing::Color Aspose::Slides::Ink::IInkBrush::get_Color()=0
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
* เนมสเปซ [Aspose::Slides::Ink](../../)
* ไลบรารี [Aspose.Slides](../../../)