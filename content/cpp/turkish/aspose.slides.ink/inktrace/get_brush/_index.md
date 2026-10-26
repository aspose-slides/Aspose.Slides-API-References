---
title: get_Brush()
second_title: Aspose.Slides için C++ API Referansı
description: IInkLine için Brush'ı alır IInkBrush Salt-okunur.
type: docs
weight: 1
url: /tr/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() yöntemi


IInkLine için Brush'ı alır [IInkBrush](../../iinkbrush/) Salt-okunur.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInkBrush](../../iinkbrush/)
* Class [InkTrace](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)