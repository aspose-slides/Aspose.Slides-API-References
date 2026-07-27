---
title: get_PrintSlideNumbers()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica si se deben imprimir o no los números de diapositiva mostrados.
type: docs
weight: 27
url: /es/aspose.slides.export/handoutlayoutingoptions/get_printslidenumbers/
---
## HandoutLayoutingOptions::get_PrintSlideNumbers() const método


Especifica si se deben imprimir o no los números de diapositiva mostrados.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintSlideNumbers() const
```

## Observaciones


El valor predeterminado es **true**. 

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Ver también

* Clase [HandoutLayoutingOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)