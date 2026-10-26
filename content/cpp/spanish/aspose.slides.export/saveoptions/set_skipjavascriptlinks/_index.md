---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides para la referencia de la API de C++
description: Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Escriba bool. El valor predeterminado es false.
type: docs
weight: 118
url: /es/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) método

Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Escriba **bool**. El valor predeterminado es **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## Observaciones

Cuando esta propiedad se establece en **true**, los hipervínculos con llamadas a JavaScript serán ignorados al guardar.

Cuando esta propiedad se establece en **false**, todos los hipervínculos se guardarán.

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