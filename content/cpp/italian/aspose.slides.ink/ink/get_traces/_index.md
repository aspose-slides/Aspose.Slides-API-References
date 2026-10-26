---
title: get_Traces()
second_title: Riferimento API Aspose.Slides per C++
description: Recupera tutte le tracce contenute nell'elemento IInk IInkTrace. Solo lettura.
type: docs
weight: 1
url: /it/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() metodo


Recupera tutte le tracce contenute nell'elemento [IInk](../../iink/) [IInkTrace](../../iinktrace/). Solamente lettura.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
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
* Classe [Ink](../)
* Spazio dei nomi [Aspose::Slides::Ink](../../)
* Libreria [Aspose.Slides](../../../)