---
title: get_Brush()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá Brush pro IInkLine IInkBrush Pouze pro čtení.
type: docs
weight: 1
url: /cs/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() metoda


Získá Brush pro IInkLine [IInkBrush](../../iinkbrush/) Pouze pro čtení.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IInkBrush](../../iinkbrush/)
* Třída [InkTrace](../)
* Jmenný prostor [Aspose::Slides::Ink](../../)
* Knihovna [Aspose.Slides](../../../)