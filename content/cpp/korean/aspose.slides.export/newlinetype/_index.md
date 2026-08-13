---
title: NewLineType
second_title: Aspose.Slides C++용 API 레퍼런스
description: 생성된 문서에서 사용될 새 줄의 유형입니다.
type: docs
weight: 963
url: /ko/aspose.slides.export/newlinetype/
---
## NewLineType 열거형

생성된 문서에서 사용할 새 줄 유형입니다.

```cpp
enum class NewLineType
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Windows | 0 | DOS 및 Windows OS 새 줄 - \r\n |
| Unix | 1 | Unix 및 Mac OS X 새 줄 - \n |
| Mac | 2 | Mac (OS 9) 새 줄 - \r |

## 비고

예시
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