---
title: get_Traces()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft alle Spuren ab, die im IInk-Element IInkTrace enthalten sind. Nur lesbar.
type: docs
weight: 1
url: /de/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() Methode

Ruft alle Spuren ab, die im [IInk](../../iink/)-Element [IInkTrace](../../iinktrace/) enthalten sind. Nur lesbar.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Anmerkungen

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IInkTrace](../../iinktrace/)
* Klasse [Ink](../)
* Namensraum [Aspose::Slides::Ink](../../)
* Bibliothek [Aspose.Slides](../../../)