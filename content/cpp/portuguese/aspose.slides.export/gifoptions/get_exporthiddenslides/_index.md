---
title: get_ExportHiddenSlides()
second_title: Referência da API Aspose.Slides para C++
description: Determina se os slides ocultos serão exportados. O valor padrão é false.
type: docs
weight: 27
url: /pt/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() método


Determina se os slides ocultos serão exportados. O valor padrão é false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Veja Também

* Classe [GifOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)