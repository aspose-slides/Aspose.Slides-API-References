---
title: get_FontsManager()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar teckensnittshanterare. Skrivskyddad IFontsManager.
type: docs
weight: 157
url: /sv/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() metod

Returnerar teckensnittshanterare. Skrivskyddad [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Anmärkningar

Följande exempel visar hur man lägger till inbäddade teckensnitt i PowerPoint [Presentation](../).
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




## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IFontsManager](../../ifontsmanager/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)