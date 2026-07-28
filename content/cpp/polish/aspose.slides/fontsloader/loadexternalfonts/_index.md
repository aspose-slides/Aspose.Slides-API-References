---
title: LoadExternalFonts()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Dodaje dodatkowe foldery do wyszukiwania czcionek.
type: docs
weight: 1
url: /pl/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) metoda


Dodaje dodatkowe foldery do wyszukiwania czcionek.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Katalogi do odczytu dodatkowych czcionek. |
## Uwagi



Poniższy przykład pokazuje, jak wczytać własne czcionki z pliku .TTF 
```cpp
// Ścieżka do katalogu dokumentów.
System::String dataDir = u"C:\\";

// foldery do wyszukiwania czcionek
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Wczytaj czcionki z własnego katalogu czcionek
FontsLoader::LoadExternalFonts(folders);

// Wykonaj pewne operacje i renderowanie prezentacji/slajdów
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Wyczyść pamięć podręczną czcionek
FontsLoader::ClearCache();
```

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [FontsLoader](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)