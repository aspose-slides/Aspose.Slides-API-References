---
title: NewLineType
second_title: Riferimento API Aspose.Slides per C++
description: Tipo di nuova riga che verrà utilizzato nel documento generato.
type: docs
weight: 963
url: /it/aspose.slides.export/newlinetype/
---
## NewLineType enum

Tipo di nuova riga che verrà utilizzato nel documento generato.

```cpp
enum class NewLineType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Windows | 0 | DOS & Windows OS nuova riga - \r\n |
| Unix | 1 | Unix & Mac OS X nuova riga - \n |
| Mac | 2 | Mac (OS 9) nuova riga - \r |

## Osservazioni

Esempio 
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

## Vedi anche

* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)