---
title: get_FontsManager()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert fonts manager. Alleen-lezen IFontsManager.
type: docs
weight: 157
url: /nl/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() methode


Retourneert fonts manager. Alleen-lezen [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Opmerkingen


Het volgende voorbeeld laat zien hoe je ingesloten lettertypen toevoegt aan PowerPoint [Presentation](../). 
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




## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontsManager](../../ifontsmanager/)
* Klasse [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)