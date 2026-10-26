---
title: NewLineType
second_title: Aspose.Slides voor C++ API-referentie
description: Type van nieuwe regel die wordt gebruikt in het gegenereerde document.
type: docs
weight: 963
url: /nl/aspose.slides.export/newlinetype/
---
## NewLineType enum

Type van nieuwe regel die wordt gebruikt in het gegenereerde document.

```cpp
enum class NewLineType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Windows | 0 | DOS & Windows OS nieuwe regel - \r\n |
| Unix | 1 | Unix & Mac OS X nieuwe regel - \n |
| Mac | 2 | Mac (OS 9) nieuwe regel - \r |

## Opmerkingen

Voorbeeld
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"doc.md", System::IO::FileMode::OpenOrCreate);

System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(stream, slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Zie ook

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)