---
title: get_Traces()
second_title: Aspose.Slides pro C++ API Reference
description: Získá všechny stopy obsažené v elementu IInk IInkTrace. Pouze pro čtení.
type: docs
weight: 1
url: /cs/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() metoda

Získá všechny stopy obsažené v elementu [IInk](../../iink/) [IInkTrace](../../iinktrace/). Pouze pro čtení.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Poznámky

Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IInkTrace](../../iinktrace/)
* Třída [Ink](../)
* Jmenný prostor [Aspose::Slides::Ink](../../)
* Knihovna [Aspose.Slides](../../../)