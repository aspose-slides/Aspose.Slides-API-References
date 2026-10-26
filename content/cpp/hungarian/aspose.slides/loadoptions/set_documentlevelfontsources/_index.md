---
title: set_DocumentLevelFontSources()
second_title: Aspose.Slides C++ API referenciához
description: Megadja a bemutató által használandó külső betűtípusok forrásait. Ezek a betűtípusok a bemutató teljes élettartama alatt elérhetők, és nem osztottak meg más bemutatókkal.
type: docs
weight: 222
url: /hu/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) módszer

Megadja a külső betűtípusok forrásait, amelyeket a bemutató használ. Ezek a betűtípusok a bemutató teljes élettartama alatt elérhetők, és nem osztottak más bemutatókkal.

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## Megjegyzés

Az alábbi példa bemutatja, hogyan adhatók meg a PowerPointtal [Presentation](../../presentation/) használt egyéni betűtípusok.

```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// a prezentációval dolgozni
// A CustomFont1, a CustomFont2, valamint az assets\fonts és a global\fonts mappákból és azok almappáiból származó betűtípusok elérhetők a prezentáció számára
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IFontSources](../../ifontsources/)
* Osztály [LoadOptions](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)