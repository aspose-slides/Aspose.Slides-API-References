---
title: get_DocumentLevelFontSources()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica las fuentes externas que se utilizarán en la presentación. Estas fuentes están disponibles para la presentación durante toda su vida útil y no se comparten con otras presentaciones.
type: docs
weight: 209
url: /es/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() método

Especifica fuentes para fuentes externas que se utilizarán en la presentación. Estas fuentes están disponibles para la presentación durante toda su vida útil y no se comparten con otras presentaciones

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## Observaciones

El siguiente ejemplo muestra cómo especificar fuentes personalizadas usadas con PowerPoint [Presentation](../../presentation/).
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// trabajar con la presentación
// CustomFont1, CustomFont2, así como fuentes de las carpetas assets\fonts y global\fonts y sus subcarpetas están disponibles para la presentación
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontSources](../../ifontsources/)
* Clase [LoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)