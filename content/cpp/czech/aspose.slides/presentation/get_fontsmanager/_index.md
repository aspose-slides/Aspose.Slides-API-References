---
title: get_FontsManager()
second_title: Aspose.Slides pro C++ reference API
description: Vrací správce písem. Pouze pro čtení IFontsManager.
type: docs
weight: 157
url: /cs/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() metoda


Vrací správce písem. Pouze pro čtení [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Poznámky


Následující příklad ukazuje, jak přidat vložená písma do PowerPointu [Presentation](../). 
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

// Uložit prezentaci
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```



## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IFontsManager](../../ifontsmanager/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)