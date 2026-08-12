---
title: Flavor
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สเปค markdown ทั้งหมดที่ใช้ในโปรแกรม.
type: docs
weight: 924
url: /th/aspose.slides.export/flavor/
---
## Flavor enum

All markdown specifications used in program.

```cpp
enum class Flavor
```

### Values

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Github | 0 | Github รูปแบบ. |
| Gruber | 1 | Gruber รูปแบบ. |
| MultiMarkdown | 2 | Multi markdown รูปแบบ. |
| CommonMark | 3 | Common mark รูปแบบ. |
| MarkdownExtra | 4 | Markdown extra รูปแบบ. |
| Pandoc | 5 | Pandoc รูปแบบ. |
| Kramdown | 6 | Kramdown รูปแบบ. |
| Markua | 7 | Markua รูปแบบ. |
| Maruku | 8 | Maruku รูปแบบ. |
| Markdown2 | 9 | Markdown2 รูปแบบ. |
| Remarkable | 10 | Remarkable รูปแบบ |
| Showdown | 11 | Showdown รูปแบบ. |
| Ghost | 12 | Ghost รูปแบบ. |
| GitLab | 13 | Gitlab รูปแบบ. |
| Haroopad | 14 | Haroopad รูปแบบ. |
| IaWriter | 15 | IAWriter รูปแบบ. |
| Redcarpet | 16 | Redcarpet รูปแบบ. |
| ScholarlyMarkdown | 17 | Scholarly markdown รูปแบบ. |
| Taiga | 18 | Taiga รูปแบบ. |
| Trello | 19 | Trello รูปแบบ. |
| S9ETextFormatter | 20 | S9E text formatter รูปแบบ. |
| XWiki | 21 | XWiki รูปแบบ. |
| StackOverflow | 22 | Stack overflow รูปแบบ. |
| Default | 23 | Default markdown รูปแบบ. |

## หมายเหตุ

ตัวอย่าง:
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

## ดูเพิ่มเติม

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)