---
title: get_Brush()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar Brush för IInkLine IInkBrush Skrivskyddad.
type: docs
weight: 1
url: /sv/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() metod

Hämtar Brush för IInkLine [IInkBrush](../../iinkbrush/) Skrivskyddad.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## Anmärkningar

Exempel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IInkBrush](../../iinkbrush/)
* Klass [IInkTrace](../)
* Namnrymd [Aspose::Slides::Ink](../../)
* Bibliotek [Aspose.Slides](../../../)