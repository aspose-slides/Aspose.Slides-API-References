---
title: Flavor
second_title: Aspose.Slides for C++ API 참조
description: 프로그램에서 사용되는 모든 마크다운 사양.
type: docs
weight: 924
url: /ko/aspose.slides.export/flavor/
---
## Flavor 열거형

모든 프로그램에서 사용되는 마크다운 사양.

```cpp
enum class Flavor
```

### 값

| Name | Value | Description |
| --- | --- | --- |
| Github | 0 | Github 플레버. |
| Gruber | 1 | Gruber 플레버. |
| MultiMarkdown | 2 | Multi markdown 플레버. |
| CommonMark | 3 | Common mark 플레버. |
| MarkdownExtra | 4 | Markdown extra 플레버. |
| Pandoc | 5 | Pandoc 플레버. |
| Kramdown | 6 | Kramdown 플레버. |
| Markua | 7 | Markua 플레버. |
| Maruku | 8 | Maruku 플레버. |
| Markdown2 | 9 | Markdown2 플레버. |
| Remarkable | 10 | Remarkable 플레버 |
| Showdown | 11 | Showdown 플레버. |
| Ghost | 12 | Ghost 플레버. |
| GitLab | 13 | Gitlab 플레버. |
| Haroopad | 14 | Haroopad 플레버. |
| IaWriter | 15 | IAWriter 플레버. |
| Redcarpet | 16 | Redcarpet 플레버. |
| ScholarlyMarkdown | 17 | Scholarly markdown 플레버. |
| Taiga | 18 | Taiga 플레버. |
| Trello | 19 | Trello 플레버. |
| S9ETextFormatter | 20 | S9E text formatter 플레버. |
| XWiki | 21 | XWiki 플레버. |
| StackOverflow | 22 | Stack overflow 플레버. |
| Default | 23 | 기본 마크다운 플레버. |

## 비고

예:
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

## 참고

* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)