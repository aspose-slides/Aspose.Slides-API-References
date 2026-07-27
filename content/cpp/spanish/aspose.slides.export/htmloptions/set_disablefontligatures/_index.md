---
title: set_DisableFontLigatures()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece un valor que indica si el texto se representa sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en false.
type: docs
weight: 105
url: /es/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) método

Establece un valor que indica si el texto se representa sin utilizar ligaduras. Cuando se establece en **true**, las ligaduras estarán deshabilitadas en la salida renderizada. Por defecto, esta propiedad se establece en **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
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