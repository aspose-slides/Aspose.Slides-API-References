---
title: set_DocumentLevelFontSources()
second_title: Aspose.Slides pro C++ reference API
description: Určuje zdroje externích písem, která jsou používána v prezentaci. Tato písma jsou v prezentaci k dispozici po celou dobu jejího životního cyklu a nejsou sdílena s jinými prezentacemi
type: docs
weight: 222
url: /cs/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) metoda


Určuje zdroje externích písem, které budou použity v prezentaci. Tato písma jsou k dispozici prezentaci po celou dobu jejího životního cyklu a nejsou sdílena s jinými prezentacemi

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## Poznámky


Následující příklad ukazuje, jak zadat vlastní písma používaná v PowerPoint [Presentation](../../presentation/).
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// pracujte s prezentací
// CustomFont1, CustomFont2 stejně jako písma ze složek assets\fonts a global\fonts a jejich podadresářů jsou k dispozici prezentaci
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IFontSources](../../ifontsources/)
* třída [LoadOptions](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)