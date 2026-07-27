---
title: get_EmbedImages()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve la opción de incrustación de imágenes. Lectura bool.
type: docs
weight: 53
url: /es/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() método


Devuelve la opción de incrustación de imágenes. Lectura **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Ver también

* Clase [Html5Options](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)