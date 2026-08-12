---
title: get_Size()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: รับขนาดแปรงสำหรับเส้นในหน่วยจุด.
type: docs
weight: 27
url: /th/aspose.slides.ink/iinkbrush/get_size/
---
## IInkBrush::get_Size() เมธอด

รับขนาดแปรงสำหรับเส้นในหน่วยจุด.

```cpp
virtual System::Drawing::SizeF Aspose::Slides::Ink::IInkBrush::get_Size()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## ดูเพิ่มเติม

* คลาส [SizeF](../../../system.drawing/sizef/)
* คลาส [IInkBrush](../)
* เนมสเปซ [Aspose::Slides::Ink](../../)
* ไลบรารี [Aspose.Slides](../../../)