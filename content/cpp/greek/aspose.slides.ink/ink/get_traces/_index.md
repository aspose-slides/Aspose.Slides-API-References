---
title: get_Traces()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντλεί όλα τα ίχνη που περιέχονται στο στοιχείο IInk IInkTrace. Μόνο για ανάγνωση.
type: docs
weight: 1
url: /el/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() μέθοδος

Αντλεί όλα τα ίχνη που περιέχονται στο στοιχείο [IInk](../../iink/) [IInkTrace](../../iinktrace/). Μόνο για ανάγνωση.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Δείτε επίσης

* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IInkTrace](../../iinktrace/)
* Κλάση [Ink](../)
* Χώρος ονομάτων [Aspose::Slides::Ink](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)