---
title: get_FontsManager()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el administrador de fuentes. Solo lectura IFontsManager.
type: docs
weight: 157
url: /es/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() método


Devuelve el administrador de fuentes. Solo lectura [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Observaciones


El siguiente ejemplo muestra cómo agregar fuentes incrustadas a PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"Fonts.pptx");
System::ArrayPtr<System::SharedPtr<IFontData>> allFonts = presentation->get_FontsManager()->GetFonts();
System::ArrayPtr<System::SharedPtr<IFontData>> embeddedFonts = presentation->get_FontsManager()->GetEmbeddedFonts();

for (auto&& font : allFonts)
{
    if (!embeddedFonts->Contains(font))
    {
        presentation->get_FontsManager()->AddEmbeddedFont(font, EmbedFontCharacters::All);
    }
}

// Save the presentation
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```




## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontsManager](../../ifontsmanager/)
* Clase [Presentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)