---
title: LoadExternalFonts()
second_title: Aspose.Slides pro referenci API C++
description: Přidá další složky pro vyhledávání fontů.
type: docs
weight: 1
url: /cs/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) metoda

Přidá další složky pro hledání fontů.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Složky, ze kterých se mají načíst další fonty. |
## Poznámky

Následující příklady ukazují, jak načíst vlastní fonty z .TTF 
```cpp
// Cesta k adresáři dokumentů.
System::String dataDir = u"C:\\";

// složky pro vyhledávání fontů
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Načíst vlastní fonty z adresáře
FontsLoader::LoadExternalFonts(folders);

// Proveďte nějakou práci a vykreslete prezentaci/snímky
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Vymazat cache fontů
FontsLoader::ClearCache();
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* třída [String](../../../system/string/)
* třída [FontsLoader](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)