---
title: get_Brush()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene Brush per l'IInkLine IInkBrush di sola lettura.
type: docs
weight: 1
url: /it/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() metodo

Ottiene Brush per l'IInkLine [IInkBrush](../../iinkbrush/) di sola lettura.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## Osservazioni

Esempio:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInkBrush](../../iinkbrush/)
* Classe [IInkTrace](../)
* Namespace [Aspose::Slides::Ink](../../)
* Libreria [Aspose.Slides](../../../)