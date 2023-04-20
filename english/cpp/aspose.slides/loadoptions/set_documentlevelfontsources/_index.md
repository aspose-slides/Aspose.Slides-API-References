---
title: set_DocumentLevelFontSources()
second_title: Aspose.Slides for C++ API Reference
description: Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations
type: docs
weight: 222
url: /cpp/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) method


Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## Remarks


The following example shows how to specify custom fonts used with PowerPoint [Presentation](../../presentation/). 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// work with the presentation
// CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSources](../../ifontsources/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)