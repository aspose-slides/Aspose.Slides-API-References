---
title: set_Color()
second_title: Aspose.Slides için C++ API Referansı
description: Bir çizgi için fırça rengini ayarlar.
type: docs
weight: 14
url: /tr/aspose.slides.ink/inkbrush/set_color/
---
## InkBrush::set_Color(System::Drawing::Color) yöntemi


Bir çizgi için fırça rengini ayarlar.

```cpp
void Aspose::Slides::Ink::InkBrush::set_Color(System::Drawing::Color value) override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Diğer Bağlantılar

* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [InkBrush](../)
* İsim Alanı [Aspose::Slides::Ink](../../)
* Kütüphane [Aspose.Slides](../../../)