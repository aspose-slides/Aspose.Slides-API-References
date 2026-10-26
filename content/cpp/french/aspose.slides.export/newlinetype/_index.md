---
title: NewLineType
second_title: Référence de l'API Aspose.Slides for C++
description: Type de nouvelle ligne qui sera utilisé dans le document généré.
type: docs
weight: 963
url: /fr/aspose.slides.export/newlinetype/
---
## NewLineType enum

Type de nouvelle ligne qui sera utilisé dans le document généré.

```cpp
enum class NewLineType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Windows | 0 | DOS & Windows OS nouvelle ligne - \r\n |
| Unix | 1 | Unix & Mac OS X nouvelle ligne - \n |
| Mac | 2 | Mac (OS 9) nouvelle ligne - \r |

## Remarques

Exemple 
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

## Voir aussi

* Espace de noms [Aspose::Slides::Export](../)
* Bibliothèque [Aspose.Slides](../../)