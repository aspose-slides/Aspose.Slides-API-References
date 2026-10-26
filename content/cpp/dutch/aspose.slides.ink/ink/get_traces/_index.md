---
title: get_Traces()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt alle sporen op die zich bevinden in het IInk-element IInkTrace. Alleen-lezen.
type: docs
weight: 1
url: /nl/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() methode


Haalt alle sporen op die zich bevinden in het [IInk](../../iink/) element [IInkTrace](../../iinktrace/). Alleen-lezen.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInkTrace](../../iinktrace/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)