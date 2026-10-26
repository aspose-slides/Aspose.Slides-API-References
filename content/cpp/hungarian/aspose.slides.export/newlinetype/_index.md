---
title: NewLineType
second_title: Aspose.Slides C++ API-referencia
description: Az elkészített dokumentumban használandó új sor típusa.
type: docs
weight: 963
url: /hu/aspose.slides.export/newlinetype/
---
## NewLineType enum

Az elkészített dokumentumban használandó új sor típusa.

```cpp
enum class NewLineType
```

### Values

| Név | Érték | Leírás |
| --- | --- | --- |
| Windows | 0 | DOS és Windows OS új sor - \r\n |
| Unix | 1 | Unix és Mac OS X új sor - \n |
| Mac | 2 | Mac (OS 9) új sor - \r |

## Megjegyzések


Példa 
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

## Lásd még

* Névterület [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)