---
title: get_DisableFontLigatures()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. De forma predeterminada, esta propiedad está establecida en false.
type: docs
weight: 92
url: /es/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() método


Obtiene un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en **true**, las ligaduras se desactivarán en la salida renderizada. De forma predeterminada, esta propiedad está establecida en **false**.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Desactivar ligaduras en la renderización del texto

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Ver también

* Clase [HtmlOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)