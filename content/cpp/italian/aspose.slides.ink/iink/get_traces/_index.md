---
title: get_Traces()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce tutte le tracce contenute nell'elemento IInk IInkTrace. Sola lettura.
type: docs
weight: 1
url: /it/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() metodo


Restituisce tutte le tracce contenute nell'elemento [IInk](../) [IInkTrace](../../iinktrace/). Sola lettura.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInkTrace](../../iinktrace/)
* Classe [IInk](../)
* Namespace [Aspose::Slides::Ink](../../)
* Libreria [Aspose.Slides](../../../)