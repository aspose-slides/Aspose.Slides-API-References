---
title: LoadExternalFonts()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt extra mappen toe om lettertypen te zoeken.
type: docs
weight: 1
url: /nl/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) methode

Voegt extra mappen toe om lettertypen te zoeken.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Mappen om extra lettertypen te lezen. |

## Opmerkingen

Het volgende voorbeeld toont hoe je aangepaste lettertypen laadt vanaf .TTF
```cpp
// Het pad naar de documentmap.
System::String dataDir = u"C:\\";

// Mappen om lettertypen te zoeken
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Laad de aangepaste lettertype map fonts
FontsLoader::LoadExternalFonts(folders);

// Doe wat werk en voer presentatie/diavoorstelling rendering uit
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Wis lettertype cache
FontsLoader::ClearCache();
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [FontsLoader](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)