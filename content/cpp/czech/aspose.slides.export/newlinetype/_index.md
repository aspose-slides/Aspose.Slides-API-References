---
title: NewLineType
second_title: Aspose.Slides pro C++ API reference
description: Typ nového řádku, který bude použit v generovaném dokumentu.
type: docs
weight: 963
url: /cs/aspose.slides.export/newlinetype/
---
## NewLineType enum

Typ nového řádku, který bude použit v generovaném dokumentu.

```cpp
enum class NewLineType
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Windows | 0 | DOS a Windows OS nový řádek - \r\n |
| Unix | 1 | Unix a Mac OS X nový řádek - \n |
| Mac | 2 | Mac (OS 9) nový řádek - \r |

## Poznámky

Příklad
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

## Viz také

* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)