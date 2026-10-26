---
title: get_SkipJavaScriptLinks()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Lectura bool. El valor predeterminado es false.
type: docs
weight: 105
url: /es/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() método


Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Lectura **bool**. El valor predeterminado es **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## Observaciones


Cuando esta propiedad está establecida en **true**, los hipervínculos con llamadas a JavaScript serán ignorados al guardar.

Cuando esta propiedad está establecida en **false**, se guardarán todos los hipervínculos.

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Véase también

* Clase [ISaveOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)