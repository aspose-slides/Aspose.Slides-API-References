---
title: Flavor
second_title: Référence de l'API Aspose.Slides pour C++
description: Toutes les spécifications markdown utilisées dans le programme.
type: docs
weight: 924
url: /fr/aspose.slides.export/flavor/
---
## Enum de saveur

Toutes les spécifications markdown utilisées dans le programme.

```cpp
enum class Flavor
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Github | 0 | Github saveur. |
| Gruber | 1 | Gruber saveur. |
| MultiMarkdown | 2 | Multi markdown saveur. |
| CommonMark | 3 | Common mark saveur. |
| MarkdownExtra | 4 | Markdown extra saveur. |
| Pandoc | 5 | Pandoc saveur. |
| Kramdown | 6 | Kramdown saveur. |
| Markua | 7 | Markua saveur. |
| Maruku | 8 | Maruku saveur. |
| Markdown2 | 9 | Markdown2 saveur. |
| Remarkable | 10 | Remarkable saveur |
| Showdown | 11 | Showdown saveur. |
| Ghost | 12 | Ghost saveur. |
| GitLab | 13 | Gitlab saveur. |
| Haroopad | 14 | Haroopad saveur. |
| IaWriter | 15 | IAWriter saveur. |
| Redcarpet | 16 | Redcarpet saveur. |
| ScholarlyMarkdown | 17 | Scholarly markdown saveur. |
| Taiga | 18 | Taiga saveur. |
| Trello | 19 | Trello saveur. |
| S9ETextFormatter | 20 | S9E text formatter saveur. |
| XWiki | 21 | XWiki saveur. |
| StackOverflow | 22 | Stack overflow saveur. |
| Default | 23 | Saveur markdown par défaut. |

## Remarques

Exemple:
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