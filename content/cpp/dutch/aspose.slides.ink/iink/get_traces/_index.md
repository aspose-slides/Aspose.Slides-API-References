---
title: get_Traces()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt alle sporen op die zich bevinden in het IInk element IInkTrace. Alleen-lezen.
type: docs
weight: 1
url: /nl/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() method


Haalt alle sporen op die zich bevinden in het [IInk](../) element [IInkTrace](../../iinktrace/). Alleen-lezen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
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
* Klasse [IInkTrace](../../iinktrace/)
* Klasse [IInk](../)
* Naamruimte [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)