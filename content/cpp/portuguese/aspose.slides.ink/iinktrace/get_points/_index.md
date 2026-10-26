---
title: get_Points()
second_title: Aspose.Slides para C++ Referência da API
description: "Obtém os pontos da IInkLine System::Drawing::PointF Somente leitura."
type: docs
weight: 14
url: /pt/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() método

Obtém os pontos da IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Somente leitura.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## Observações

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* classe [PointF](../../../system.drawing/pointf/)
* classe [IInkTrace](../)
* espaço de nomes [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)