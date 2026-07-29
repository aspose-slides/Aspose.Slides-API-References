---
title: LoadExternalFonts()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till ytterligare mappar för att söka teckensnitt.
type: docs
weight: 1
url: /sv/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) metod

Lägger till ytterligare mappar för att söka teckensnitt.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Kataloger för att läsa ytterligare teckensnitt. |
## Anmärkningar

Följande exempel visar hur man laddar anpassade teckensnitt från .TTF
```cpp
// Sökvägen till dokumentkatalogen.
System::String dataDir = u"C:\\";

// mappar för att söka teckensnitt
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Ladda anpassade teckensnitt från katalogen
FontsLoader::LoadExternalFonts(folders);

// Utför lite arbete och rendera presentation/slide
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Rensa teckensnittscache
FontsLoader::ClearCache();
```

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [FontsLoader](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)