---
title: get_Brush()
second_title: Referência da API Aspose.Slides para C++
description: Obtém Brush para o IInkLine IInkBrush Somente leitura.
type: docs
weight: 1
url: /pt/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() método


Obtém Brush para o IInkLine [IInkBrush](../../iinkbrush/) Somente leitura.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInkBrush](../../iinkbrush/)
* Classe [IInkTrace](../)
* Espaço de nomes [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)