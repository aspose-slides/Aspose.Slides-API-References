---
title: get_Size()
second_title: Aspose.Slides per il riferimento API C++
description: Restituisce la dimensione del pennello per una linea in punti.
type: docs
weight: 27
url: /it/aspose.slides.ink/iinkbrush/get_size/
---
## IInkBrush::get_Size() metodo

Restituisce la dimensione del pennello per una linea in punti.

```cpp
virtual System::Drawing::SizeF Aspose::Slides::Ink::IInkBrush::get_Size()=0
```

## Osservazioni

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Vedi anche

* Classe [SizeF](../../../system.drawing/sizef/)
* Classe [IInkBrush](../)
* Spazio dei nomi [Aspose::Slides::Ink](../../)
* Libreria [Aspose.Slides](../../../)