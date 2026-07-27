---
title: set_ExportHiddenSlides()
second_title: Referência da API Aspose.Slides para C++
description: Determina se os slides ocultos serão exportados. O valor padrão é falso.
type: docs
weight: 40
url: /pt/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) método


Determina se os slides ocultos serão exportados. O valor padrão é falso.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Ver também

* Classe [IGifOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)