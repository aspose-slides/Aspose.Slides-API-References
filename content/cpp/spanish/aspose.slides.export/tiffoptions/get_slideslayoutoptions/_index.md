---
title: get_SlidesLayoutOptions()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el modo en que las diapositivas se colocan en la página al exportar una presentación ISlidesLayoutOptions.
type: docs
weight: 170
url: /es/aspose.slides.export/tiffoptions/get_slideslayoutoptions/
---
## TiffOptions::get_SlidesLayoutOptions() método


Obtiene el modo en el que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::TiffOptions::get_SlidesLayoutOptions() override
```

## Observaciones


Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Clase [TiffOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)