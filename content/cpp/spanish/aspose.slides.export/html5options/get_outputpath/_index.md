---
title: get_OutputPath()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Determina dónde se deben almacenar los recursos externos. Lea System::String."
type: docs
weight: 79
url: /es/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() método


Determina dónde se deben almacenar los recursos externos. Lea [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [Html5Options](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)