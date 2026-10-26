---
title: set_DocumentLevelFontSources()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica fontes externas a serem usadas pela apresentação. Essas fontes estão disponíveis para a apresentação ao longo de sua vida útil e não são compartilhadas com outras apresentações
type: docs
weight: 222
url: /pt/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) método

Especifica fontes externas a serem usadas pela apresentação. Essas fontes estão disponíveis para a apresentação durante todo o seu tempo de vida e não são compartilhadas com outras apresentações

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
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
// CustomFont1, CustomFont2 bem como fontes das pastas assets\fonts e global\fonts e suas subpastas estão disponíveis para a apresentação
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontSources](../../ifontsources/)
* Classe [LoadOptions](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)