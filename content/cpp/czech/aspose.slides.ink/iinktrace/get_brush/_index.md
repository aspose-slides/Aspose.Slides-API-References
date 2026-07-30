---
title: get_Brush()
second_title: Aspose.Slides pro C++ API Reference
description: Získá Brush pro IInkLine IInkBrush pouze pro čtení.
type: docs
weight: 1
url: /cs/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() metoda


Získá Brush pro IInkLine [IInkBrush](../../iinkbrush/) pouze pro čtení.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
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
* Třída [IInkTrace](../)
* Jmenný prostor [Aspose::Slides::Ink](../../)
* Knihovna [Aspose.Slides](../../../)