---
title: get_Traces()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera wszystkie ślady zawarte w elemencie IInk IInkTrace. Tylko do odczytu.
type: docs
weight: 1
url: /pl/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() metoda

Pobiera wszystkie ślady zawarte w elemencie [IInk](../) [IInkTrace](../../iinktrace/). Tylko do odczytu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## Uwagi

Przykład:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IInkTrace](../../iinktrace/)
* Klasa [IInk](../)
* Przestrzeń nazw [Aspose::Slides::Ink](../../)
* Biblioteka [Aspose.Slides](../../../)