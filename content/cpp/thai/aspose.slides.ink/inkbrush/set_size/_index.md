---
title: set_Size()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตั้งค่าขนาดแปรงสำหรับเส้นในหน่วย point.
type: docs
weight: 40
url: /th/aspose.slides.ink/inkbrush/set_size/
---
## InkBrush::set_Size(System::Drawing::SizeF) เมธอด

ตั้งค่าขนาดแปรงสำหรับเส้นในหน่วย point.

```cpp
void Aspose::Slides::Ink::InkBrush::set_Size(System::Drawing::SizeF value) override
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
* คลาส [InkBrush](../)
* เนมสเปซ [Aspose::Slides::Ink](../../)
* ไลบรารี [Aspose.Slides](../../../)