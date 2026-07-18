---
title: get_Color()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Αποκτά το χρώμα πινέλου για μια γραμμή.
type: docs
weight: 1
url: /el/aspose.slides.ink/inkbrush/get_color/
---
## InkBrush::get_Color() μέθοδος


Αποκτά το χρώμα πινέλου για μια γραμμή.

```cpp
System::Drawing::Color Aspose::Slides::Ink::InkBrush::get_Color() override
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
* Κλάση [InkBrush](../)
* Χώρος ονομάτων [Aspose::Slides::Ink](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)