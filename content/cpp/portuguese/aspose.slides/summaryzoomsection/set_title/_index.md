---
title: set_Title()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o título de texto do objeto Summary Zoom Section.
type: docs
weight: 14
url: /pt/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) método


Retorna o título de texto do objeto Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Ver também

* Classe [String](../../../system/string/)
* Classe [SummaryZoomSection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)