---
title: MarkdownExportType
second_title: Aspose.Slides for C++ API 레퍼런스
description: 렌더링 문서 유형.
type: docs
weight: 950
url: /ko/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum

문서를 렌더링하는 유형.

```cpp
enum class MarkdownExportType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Sequential | 0 | 모든 항목을 개별적으로 렌더링합니다. 하나씩. |
| TextOnly | 1 | 텍스트만 렌더링합니다. |
| Visual | 2 | 모든 항목을 렌더링합니다. 그룹화된 항목은 함께 렌더링합니다. |

## Remarks

예:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## See Also

* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)