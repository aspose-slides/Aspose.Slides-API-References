---
title: get_SkipJavaScriptLinks()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Lectura bool. El valor predeterminado es false.
type: docs
weight: 105
url: /es/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() método


Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Lectura **bool**. El valor predeterminado es **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## Observaciones


Cuando esta propiedad se establece en **true**, los hipervínculos con llamadas a JavaScript serán ignorados al guardar.

Cuando esta propiedad se establece en **false**, se guardarán todos los hipervínculos.

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Ver también

* Clase [SaveOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)