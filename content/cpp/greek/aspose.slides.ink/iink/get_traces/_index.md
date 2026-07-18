---
title: get_Traces()
second_title: Αναφορά API Aspose.Slides για C++
description: Αποκτά όλα τα ίχνη που περιέχονται στο στοιχείο IInk IInkTrace. Μόνο για ανάγνωση.
type: docs
weight: 1
url: /el/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() μέθοδος

Αποκτά όλα τα ίχνη που περιέχονται στο στοιχείο [IInk](../) [IInkTrace](../../iinktrace/). Μόνο για ανάγνωση.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IInkTrace](../../iinktrace/)
* Κλάση [IInk](../)
* Χώρος ονομάτων [Aspose::Slides::Ink](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)