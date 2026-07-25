---
title: NewLineType
second_title: Aspose.Slides for C++ API リファレンス
description: 生成された文書で使用される改行の種類です。
type: docs
weight: 963
url: /ja/aspose.slides.export/newlinetype/
---
## NewLineType 列挙型

生成された文書で使用される改行タイプです。

```cpp
enum class NewLineType
```

### Values

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Windows | 0 | DOS および Windows OS の改行 - \r\n |
| Unix | 1 | Unix および Mac OS X の改行 - \n |
| Mac | 2 | Mac (OS 9) の改行 - \r |

## 備考

例
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

## 参照

* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)