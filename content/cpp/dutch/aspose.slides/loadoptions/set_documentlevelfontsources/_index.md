---
title: set_DocumentLevelFontSources()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de volledige levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties
type: docs
weight: 222
url: /nl/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) methode

Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de volledige levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## Opmerkingen

Het volgende voorbeeld toont hoe u aangepaste lettertypen kunt specificeren die met PowerPoint [Presentation](../../presentation/) worden gebruikt. 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// werk met de presentatie
// CustomFont1, CustomFont2 evenals lettertypen uit de mappen assets\fonts & global\fonts en hun submappen zijn beschikbaar voor de presentatie
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontSources](../../ifontsources/)
* Klasse [LoadOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)