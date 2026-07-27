---
title: set_Description()
second_title: Aspose.Slides para Referência da API C++
description: Retorna a descrição de texto do objeto Summary Zoom Section.
type: docs
weight: 40
url: /pt/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) método


Retorna a descrição de texto do objeto Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
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
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)