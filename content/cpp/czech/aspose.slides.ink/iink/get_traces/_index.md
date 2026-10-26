---
title: get_Traces()
second_title: Aspose.Slides pro C++ API Reference
description: Získá všechny stopy obsažené v elementu IInk IInkTrace. Pouze pro čtení.
type: docs
weight: 1
url: /cs/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() metoda

Získá všechny stopy obsažené v elementu [IInk](../) [IInkTrace](../../iinktrace/). Pouze pro čtení.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## Poznámky

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Viz také

* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IInkTrace](../../iinktrace/)
* Třída [IInk](../)
* Jmenný prostor [Aspose::Slides::Ink](../../)
* Knihovna [Aspose.Slides](../../../)