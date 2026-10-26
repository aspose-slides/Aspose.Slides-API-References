---
title: get_Description()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a descrição de texto do objeto Summary Zoom Section.
type: docs
weight: 27
url: /pt/aspose.slides/isummaryzoomsection/get_description/
---
## ISummaryZoomSection::get_Description() method


Retorna a descrição de texto do objeto Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Description()=0
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
* Classe [ISummaryZoomSection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)