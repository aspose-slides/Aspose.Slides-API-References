---
title: get_Size()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει το μέγεθος της βούρτσας για μια γραμμή σε πόντους.
type: docs
weight: 27
url: /el/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() μέθοδος


Λαμβάνει το μέγεθος της βούρτσας για μια γραμμή σε πόντους.

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Δείτε επίσης

* Κλάση [SizeF](../../../system.drawing/sizef/)
* Κλάση [InkBrush](../)
* Χώρος ονομάτων [Aspose::Slides::Ink](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)