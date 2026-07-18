---
title: get_Color()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει το χρώμα του πινέλου για μια γραμμή.
type: docs
weight: 1
url: /el/aspose.slides.ink/iinkbrush/get_color/
---
## IInkBrush::get_Color() μέθοδος

Λαμβάνει το χρώμα του πινέλου για μια γραμμή.

```cpp
virtual System::Drawing::Color Aspose::Slides::Ink::IInkBrush::get_Color()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Δείτε επίσης

* Κλάση [Color](../../../system.drawing/color/)
* Κλάση [IInkBrush](../)
* Χώρος ονομάτων [Aspose::Slides::Ink](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)