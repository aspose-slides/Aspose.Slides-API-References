---
title: get_Brush()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera Brush dla IInkLine IInkBrush tylko do odczytu.
type: docs
weight: 1
url: /pl/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() metoda


Pobiera Brush dla IInkLine [IInkBrush](../../iinkbrush/) Tylko do odczytu.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IInkBrush](../../iinkbrush/)
* Klasa [InkTrace](../)
* Przestrzeń nazw [Aspose::Slides::Ink](../../)
* Biblioteka [Aspose.Slides](../../../)