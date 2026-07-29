---
title: get_DocumentLevelFontSources()
second_title: Aspose.Slides för C++ API-referens
description: Anger källor för externa teckensnitt som ska användas av presentationen. Dessa teckensnitt är tillgängliga för presentationen under hela dess livstid och delas inte med andra presentationer
type: docs
weight: 209
url: /sv/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() metod

Anger källor för externa typsnitt som ska användas av presentationen. Dessa typsnitt är tillgängliga för presentationen under hela dess livstid och delas inte med andra presentationer

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## Anmärkningar

Följande exempel visar hur man specificerar anpassade typsnitt som används med PowerPoint [Presentation](../../presentation/). 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// arbeta med presentationen
// CustomFont1, CustomFont2 samt teckensnitt från mapparna assets\fonts och global\fonts samt deras undermappar är tillgängliga för presentationen
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IFontSources](../../ifontsources/)
* Klass [LoadOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)