---
title: set_SkipJavaScriptLinks()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Escriba bool. El valor predeterminado es false.
type: docs
weight: 118
url: /es/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) método


Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Escribe **bool**. El valor predeterminado es **false**.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## Observaciones


Cuando esta propiedad se establece en **true**, los hipervínculos con llamadas a JavaScript se ignorarán al guardar.

Cuando esta propiedad se establece en **false**, se guardarán todos los hipervínculos.

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Ver también

* Clase [ISaveOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)