---
title: get_OutputPath()
second_title: Aspose.Slides para la referencia de API de C++
description: "Determina dónde deben almacenarse los recursos externos. Lea System::String."
type: docs
weight: 79
url: /es/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() método

Determina dónde deben almacenarse los recursos externos. Lea [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Observaciones

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [IHtml5Options](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)