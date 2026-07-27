---
title: get_Title()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna o título de texto do objeto Summary Zoom Section.
type: docs
weight: 1
url: /pt/aspose.slides/isummaryzoomsection/get_title/
---
## ISummaryZoomSection::get_Title() método


Retorna o título de texto do objeto Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Title()=0
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
* Classe [ISummaryZoomSection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)