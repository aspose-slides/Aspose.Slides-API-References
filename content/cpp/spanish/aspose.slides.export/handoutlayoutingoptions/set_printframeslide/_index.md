---
title: set_PrintFrameSlide()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica si se deben dibujar marcos alrededor de las diapositivas mostradas o no.
type: docs
weight: 66
url: /es/aspose.slides.export/handoutlayoutingoptions/set_printframeslide/
---
## HandoutLayoutingOptions::set_PrintFrameSlide(bool) método

Especifica si se deben dibujar marcos alrededor de las diapositivas mostradas o no.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintFrameSlide(bool value)
```

## Observaciones

El valor predeterminado es **true**. 

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintFrameSlide(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Ver también

* Clase [HandoutLayoutingOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)