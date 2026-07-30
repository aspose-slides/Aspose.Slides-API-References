---
title: set_Size()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta la dimensione del pennello per una linea in punti.
type: docs
weight: 40
url: /it/aspose.slides.ink/iinkbrush/set_size/
---
## IInkBrush::set_Size(System::Drawing::SizeF) method


Imposta la dimensione del pennello per una linea in punti.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Size(System::Drawing::SizeF value)=0
```

## Note


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