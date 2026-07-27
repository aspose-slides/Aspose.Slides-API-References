---
title: set_Description()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a descrição de texto do objeto Summary Zoom Section.
type: docs
weight: 40
url: /pt/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) método

Retorna a descrição de texto do objeto Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
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

## Veja também

* Classe [String](../../../system/string/)
* Classe [ISummaryZoomSection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)