---
title: set_OutputPath()
second_title: Referencia API de Aspose.Slides para C++
description: "Determina dónde se deben almacenar los recursos externos. Escriba System::String."
type: docs
weight: 92
url: /es/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) método


Determina dónde se deben almacenar los recursos externos. Escriba [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## Observaciones


Example: 
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