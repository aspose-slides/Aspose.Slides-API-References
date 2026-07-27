---
title: get_SlidesLayoutOptions()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el modo en que las diapositivas se colocan en la página al exportar una presentación ISlidesLayoutOptions.
type: docs
weight: 209
url: /es/aspose.slides.export/ihtmloptions/get_slideslayoutoptions/
---
## IHtmlOptions::get_SlidesLayoutOptions() method

Obtiene el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtmlOptions::get_SlidesLayoutOptions()=0
```

## Observaciones

Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Clase [IHtmlOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)