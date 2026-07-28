---
title: get_DocumentLevelFontSources()
second_title: Aspose.Slides C++ API referencia
description: Megadja a prezentáció által használandó külső betűtípusok forrásait. Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztódnak meg más prezentációkkal
type: docs
weight: 209
url: /hu/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() metódus


Meghatározza a külső betűtípusok forrásait, amelyeket a prezentáció használ. Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztódnak meg más prezentációkkal

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## Megjegyzések


A következő példában látható, hogyan lehet megadni az egyedi betűtípusokat, amelyeket a PowerPoint [Presentation](../../presentation/) használ. 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// munka a prezentációval
// A CustomFont1, CustomFont2, valamint az assets\fonts és a global\fonts mappákból és azok almappáiból származó betűtípusok elérhetők a prezentáció számára
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IFontSources](../../ifontsources/)
* Osztály [LoadOptions](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)