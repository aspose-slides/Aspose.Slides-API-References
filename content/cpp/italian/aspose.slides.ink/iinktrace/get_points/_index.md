---
title: get_Points()
second_title: Riferimento API di Aspose.Slides per C++
description: "Ottiene i punti per la IInkLine System::Drawing::PointF sola lettura."
type: docs
weight: 14
url: /it/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() metodo

Ottiene i punti per la IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) sola lettura.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## Osservazioni

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IInkTrace](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)