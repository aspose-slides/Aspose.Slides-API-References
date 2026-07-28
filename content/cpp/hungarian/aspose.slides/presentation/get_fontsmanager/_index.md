---
title: get_FontsManager()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a betűtípuskezelőt. Csak olvasható IFontsManager.
type: docs
weight: 157
url: /hu/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() metódus


Visszaadja a betűtípuskezelőt. Csak olvasható [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Megjegyzés


A következő példa bemutatja, hogyan lehet beágyazott betűtípusokat hozzáadni a PowerPointhoz [Presentation](../). 
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

// Mentse a prezentációt
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```




## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IFontsManager](../../ifontsmanager/)
* Osztály [Presentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)