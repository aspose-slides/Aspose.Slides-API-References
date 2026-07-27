---
title: set_EmbedImages()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece la opción de incrustación de imágenes. Escriba bool.
type: docs
weight: 66
url: /es/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) método

Establece la opción de incrustación de imágenes. Escriba **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
```

## Comentarios

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
* Library [Aspose.Slides](../../../)