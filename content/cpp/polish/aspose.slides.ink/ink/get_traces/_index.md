---
title: get_Traces()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Pobiera wszystkie ślady zawarte w elemencie IInk IInkTrace. Tylko do odczytu.
type: docs
weight: 1
url: /pl/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() metoda


Pobiera wszystkie ślady znajdujące się w elemencie [IInk](../../iink/) [IInkTrace](../../iinktrace/). Tylko do odczytu.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
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
* Klasa [Ink](../)
* Przestrzeń nazw [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)