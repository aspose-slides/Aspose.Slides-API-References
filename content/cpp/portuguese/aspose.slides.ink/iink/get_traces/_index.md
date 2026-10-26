---
title: get_Traces()
second_title: Referência da API Aspose.Slides para C++
description: Obtém todos os traços contidos no elemento IInk IInkTrace. Somente leitura.
type: docs
weight: 1
url: /pt/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() método

Obtém todos os traços contidos no [IInk](../) elemento [IInkTrace](../../iinktrace/). Somente leitura.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## Observações

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Veja também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInkTrace](../../iinktrace/)
* Classe [IInk](../)
* Namespace [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)