---
title: NewLineType
second_title: Aspose.Slides dla C++ – odniesienie API
description: Typ nowej linii, który będzie używany w generowanym dokumencie.
type: docs
weight: 963
url: /pl/aspose.slides.export/newlinetype/
---
## NewLineType enum


Typ nowej linii, który będzie używany w generowanym dokumencie.

```cpp
enum class NewLineType
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Windows | 0 | DOS & Windows OS nowa linia - \r\n |
| Unix | 1 | Unix & Mac OS X nowa linia - \n |
| Mac | 2 | Mac (OS 9) nowa linia - \r |

## Uwagi


Przykład
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

## Zobacz także

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)