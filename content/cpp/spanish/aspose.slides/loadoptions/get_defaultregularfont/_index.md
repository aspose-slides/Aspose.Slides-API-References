---
title: get_DefaultRegularFont()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Devuelve la fuente Regular utilizada en caso de que no se encuentre la fuente de origen. Lea System::String."
type: docs
weight: 27
url: /es/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() método

Devuelve la fuente Regular utilizada en caso de que no se encuentre la fuente de origen. Lea [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Comentarios

El siguiente ejemplo muestra cómo establecer fuentes predeterminadas para renderizar PowerPoint [Presentation](../../presentation/). 
```cpp
// Usa opciones de carga para definir las fuentes regular y asiática predeterminadas
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Cargar la presentación
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Generar miniatura de la diapositiva
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Generar PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Generar XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [LoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)