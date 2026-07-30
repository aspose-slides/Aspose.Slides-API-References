---
title: get_Brush()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene Brush per l'IInkLine IInkBrush Solo lettura.
type: docs
weight: 1
url: /it/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() metodo

Ottiene Brush per l'IInkLine [IInkBrush](../../iinkbrush/) Solo lettura.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
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
* Classe [InkTrace](../)
* Spazio dei nomi [Aspose::Slides::Ink](../../)
* Libreria [Aspose.Slides](../../../)