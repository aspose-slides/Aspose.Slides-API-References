---
title: get_Traces()
second_title: Referência da API Aspose.Slides para C++
description: Obtém todos os traços contidos no elemento IInk IInkTrace. Somente leitura.
type: docs
weight: 1
url: /pt/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() método


Obtém todos os traços contidos no elemento [IInk](../../iink/) [IInkTrace](../../iinktrace/). Somente leitura.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInkTrace](../../iinktrace/)
* Classe [Ink](../)
* Espaço de nomes [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)