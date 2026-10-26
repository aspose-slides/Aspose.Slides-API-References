---
title: set_DisableFontLigatures()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece un valor que indica si el texto se representa sin usar ligaduras. Cuando se establece a true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece a false.
type: docs
weight: 53
url: /es/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) método


Establece un valor que indica si el texto se representa sin usar ligaduras. Cuando se establece a **true**, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece a **false**.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Desactivar ligaduras en la representación de texto

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Ver también

* Clase [RenderingOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)