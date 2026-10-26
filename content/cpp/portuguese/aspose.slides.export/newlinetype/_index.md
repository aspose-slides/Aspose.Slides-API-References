---
title: NewLineType
second_title: Referência da API Aspose.Slides para C++
description: Tipo de nova linha que será usado no documento gerado.
type: docs
weight: 963
url: /pt/aspose.slides.export/newlinetype/
---
## NewLineType enum

Tipo de nova linha que será usado no documento gerado.

```cpp
enum class NewLineType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Windows | 0 | Linha nova de DOS & Windows OS - \r\n |
| Unix | 1 | Linha nova de Unix & Mac OS X - \n |
| Mac | 2 | Linha nova de Mac (OS 9) - \r |

## Observações


Exemplo 
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

## Veja Também

* Espaço de nomes [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)