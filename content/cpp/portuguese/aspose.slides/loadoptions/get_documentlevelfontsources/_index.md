---
title: get_DocumentLevelFontSources()
second_title: Referência da API Aspose.Slides para C++
description: Especifica as fontes externas a serem usadas na apresentação. Essas fontes ficam disponíveis para a apresentação durante todo o seu ciclo de vida e não são compartilhadas com outras apresentações
type: docs
weight: 209
url: /pt/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() método


Especifica as fontes externas a serem usadas na apresentação. Essas fontes ficam disponíveis para a apresentação durante todo o seu ciclo de vida e não são compartilhadas com outras apresentações

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## Observações


O exemplo a seguir mostra como especificar fontes personalizadas usadas com o PowerPoint [Presentation](../../presentation/). 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// trabalhe com a apresentação
// CustomFont1, CustomFont2, assim como fontes das pastas assets\fonts e global\fonts e suas subpastas, estão disponíveis para a apresentação
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontSources](../../ifontsources/)
* Classe [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)