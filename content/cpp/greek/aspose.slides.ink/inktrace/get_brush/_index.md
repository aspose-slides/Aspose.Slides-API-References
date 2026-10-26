---
title: get_Brush()
second_title: Aspose.Slides για C++ API Αναφορά
description: Παίρνει Brush για το IInkLine IInkBrush μόνο για ανάγνωση.
type: docs
weight: 1
url: /el/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() μέθοδος


Παίρνει Brush για το IInkLine [IInkBrush](../../iinkbrush/) μόνο για ανάγνωση.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IInkBrush](../../iinkbrush/)
* Κλάση [InkTrace](../)
* Χώρος ονομάτων [Aspose::Slides::Ink](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)