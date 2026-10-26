---
title: get_FontsManager()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca menedżer czcionek. Tylko do odczytu IFontsManager.
type: docs
weight: 157
url: /pl/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() metoda


Zwraca menedżer czcionek. Tylko do odczytu [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Uwagi


Poniższy przykład pokazuje, jak dodać osadzone czcionki do PowerPoint [Presentation](../). 
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




## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IFontsManager](../../ifontsmanager/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)