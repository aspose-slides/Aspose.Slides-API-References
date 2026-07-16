---
title: set_DocumentLevelFontSources()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie les sources des polices externes à utiliser pour la présentation. Ces polices sont disponibles pour la présentation pendant toute sa durée de vie et ne sont pas partagées avec d'autres présentations
type: docs
weight: 222
url: /fr/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) méthode

Spécifie les sources des polices externes à utiliser pour la présentation. Ces polices sont disponibles pour la présentation pendant toute sa durée de vie et ne sont pas partagées avec d'autres présentations

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## Remarques

L'exemple suivant montre comment spécifier des polices personnalisées utilisées avec PowerPoint [Presentation](../../presentation/).
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// travailler avec la présentation
// CustomFont1, CustomFont2 ainsi que les polices des dossiers assets\fonts & global\fonts et leurs sous-dossiers sont disponibles pour la présentation
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontSources](../../ifontsources/)
* Classe [LoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)