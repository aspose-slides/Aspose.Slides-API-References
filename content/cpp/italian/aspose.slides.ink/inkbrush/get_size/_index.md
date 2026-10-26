---
title: get_Size()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene la dimensione del pennello per una linea in punti.
type: docs
weight: 27
url: /it/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() metodo


Ottiene la dimensione del pennello per una linea in punti.

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
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
* Classe [InkBrush](../)
* Spazio dei nomi [Aspose::Slides::Ink](../../)
* Libreria [Aspose.Slides](../../../)