---
title: set_Handout()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica cuántas diapositivas y en qué secuencia se colocarán en la página HandoutType.
type: docs
weight: 14
url: /es/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) método

Especifica cuántas diapositivas y en qué secuencia se colocarán en la página [HandoutType](../../handouttype/).

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## Observaciones

El valor predeterminado es **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Ver también

* Enum [HandoutType](../../handouttype/)
* Clase [HandoutLayoutingOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)