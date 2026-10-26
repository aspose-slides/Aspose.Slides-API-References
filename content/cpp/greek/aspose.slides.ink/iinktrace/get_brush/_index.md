---
title: get_Brush()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει Brush για το IInkLine IInkBrush Μόνο για ανάγνωση.
type: docs
weight: 1
url: /el/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() μέθοδος

Λαμβάνει Brush για το IInkLine [IInkBrush](../../iinkbrush/) Μόνο για ανάγνωση.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
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

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IInkBrush](../../iinkbrush/)
* Κλάση [IInkTrace](../)
* Χώρος ονομάτων [Aspose::Slides::Ink](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)