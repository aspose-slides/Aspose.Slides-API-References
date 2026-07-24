---
title: NewLineType
second_title: Aspose.Slides für C++ API-Referenz
description: Typ des Zeilenumbruchs, der im erzeugten Dokument verwendet wird.
type: docs
weight: 963
url: /de/aspose.slides.export/newlinetype/
---
## NewLineType enum

Typ des Zeilenumbruchs, der im erzeugten Dokument verwendet wird.

```cpp
enum class NewLineType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Windows | 0 | DOS & Windows OS Zeilenumbruch - \r\n |
| Unix | 1 | Unix & Mac OS X Zeilenumbruch - \n |
| Mac | 2 | Mac (OS 9) Zeilenumbruch - \r |

## Hinweise

Beispiel
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

## Siehe auch

* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)