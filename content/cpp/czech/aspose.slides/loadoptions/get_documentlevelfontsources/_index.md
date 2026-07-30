---
title: get_DocumentLevelFontSources()
second_title: Aspose.Slides pro C++ API Reference
description: Specifikuje zdroje pro externí fonty, které budou použity v prezentaci. Tyto fonty jsou k dispozici prezentaci po celou dobu jejího životního cyklu a nejsou sdíleny s jinými prezentacemi
type: docs
weight: 209
url: /cs/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() metoda

Specifikuje zdroje pro externí fonty, které budou použity v prezentaci. Tyto fonty jsou k dispozici prezentaci po celou dobu jejího životního cyklu a nejsou sdíleny s jinými prezentacemi.

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## Poznámky

Následující příklad ukazuje, jak zadat vlastní fonty používané v PowerPoint [Presentation](../../presentation/).
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// pracujte s prezentací
// CustomFont1, CustomFont2 i fonty ze složek assets\fonts a global\fonts a jejich podadresářů jsou k dispozici prezentaci
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IFontSources](../../ifontsources/)
* Třída [LoadOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)