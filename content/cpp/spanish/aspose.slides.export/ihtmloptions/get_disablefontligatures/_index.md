---
title: get_DisableFontLigatures()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene un valor que indica si el texto se representa sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en false.
type: docs
weight: 183
url: /es/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() método


Obtiene un valor que indica si el texto se representa sin usar ligaduras. Cuando se establece en **true**, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
```

## Observaciones


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Desactivar ligaduras en la representación de texto

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Véase también

* Clase [IHtmlOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)