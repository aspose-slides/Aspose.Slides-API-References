---
title: set_DisableFontLigatures()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en false.
type: docs
weight: 144
url: /es/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) método

Establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en **true**, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en **false**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## Observaciones

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Desactivar ligaduras en la renderización de texto

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Ver también

* Clase [IHtml5Options](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)