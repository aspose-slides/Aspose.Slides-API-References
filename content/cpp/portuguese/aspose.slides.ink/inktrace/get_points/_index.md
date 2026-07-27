---
title: get_Points()
second_title: Referência da API Aspose.Slides para C++
description: "Obtém pontos para o IInkLine System::Drawing::PointF Somente leitura."
type: docs
weight: 14
url: /pt/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() method

Obtém pontos para o IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Somente leitura.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## Observações

Exemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [InkTrace](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)