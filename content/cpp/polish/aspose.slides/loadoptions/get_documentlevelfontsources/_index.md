---
title: get_DocumentLevelFontSources()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Określa źródła zewnętrznych czcionek używanych w prezentacji. Czcionki te są dostępne w prezentacji przez cały jej okres życia i nie są współdzielone z innymi prezentacjami
type: docs
weight: 209
url: /pl/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() metoda

Określa źródła zewnętrznych czcionek używanych w prezentacji. Czcionki te są dostępne w prezentacji przez cały jej okres życia i nie są współdzielone z innymi prezentacjami

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## Uwagi

Poniższy przykład pokazuje, jak określić niestandardowe czcionki używane w programie PowerPoint [Presentation](../../presentation/). 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// pracuj z prezentacją
// CustomFont1, CustomFont2 oraz czcionki z folderów assets\fonts i global\fonts oraz ich podfolderów są dostępne dla prezentacji
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IFontSources](../../ifontsources/)
* Klasa [LoadOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)