---
title: LoadExternalFonts()
second_title: Aspose.Slides C++ API referencia
description: További mappákat ad hozzá a betűtípusok kereséséhez.
type: docs
weight: 1
url: /hu/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) metódus


További mappákat ad hozzá a betűtípusok kereséséhez.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Könyvtárak a további betűtípusok olvasásához. |
## Megjegyzés



Az alábbi példák megmutatják, hogyan lehet egyedi betűtípusokat .TTF-ből betölteni.
```cpp
// A dokumentumok könyvtárának útvonala.
System::String dataDir = u"C:\\";

// mappák a betűtípusok kereséséhez
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Egyedi betűtípus könyvtár betöltése
FontsLoader::LoadExternalFonts(folders);

// Néhány művelet végrehajtása és a bemutató/vázlat renderelése
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Betűtípus-gyorsítótár törlése
FontsLoader::ClearCache();
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [FontsLoader](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)