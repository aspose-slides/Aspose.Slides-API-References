---
title: get_Description()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna a descrição de texto do objeto Summary Zoom Section.
type: docs
weight: 27
url: /pt/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() método

Retorna a descrição de texto do objeto Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
```

## Observações

Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Ver também

* Classe [String](../../../system/string/)
* Classe [SummaryZoomSection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)