---
title: set_DefaultRegularFont()
second_title: Referencia de API de Aspose.Slides para C++
description: "Establece la fuente Regular que se usa en caso de que no se encuentre la fuente original. Escriba System::String."
type: docs
weight: 40
url: /es/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) método

Establece la fuente Regular que se usa en caso de que no se encuentre la fuente original. Escriba [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Observaciones

El siguiente ejemplo muestra cómo establecer fuentes predeterminadas para renderizar PowerPoint [Presentation](../../presentation/). 
```cpp
// Utilice opciones de carga para definir las fuentes regular y asiática predeterminadas
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