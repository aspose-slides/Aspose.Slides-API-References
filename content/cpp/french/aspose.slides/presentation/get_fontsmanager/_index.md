---
title: get_FontsManager()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le gestionnaire de polices. En lecture seule IFontsManager.
type: docs
weight: 157
url: /fr/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() méthode

Renvoie le gestionnaire de polices. En lecture seule [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Remarques

L'exemple suivant montre comment ajouter des polices embarquées à PowerPoint [Presentation](../). 
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



## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontsManager](../../ifontsmanager/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)