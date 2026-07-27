---
title: get_SlidesLayoutOptions()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el modo en que las diapositivas se colocan en la página al exportar una presentación ISlidesLayoutOptions.
type: docs
weight: 1
url: /es/aspose.slides.export/pdfoptions/get_slideslayoutoptions/
---
## PdfOptions::get_SlidesLayoutOptions() método


Obtiene el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::PdfOptions::get_SlidesLayoutOptions() override
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Clase [PdfOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)