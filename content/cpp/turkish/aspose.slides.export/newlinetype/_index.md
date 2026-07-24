---
title: NewLineType
second_title: Aspose.Slides for C++ API Referansı
description: Oluşturulan belgede kullanılacak yeni satır türü.
type: docs
weight: 963
url: /tr/aspose.slides.export/newlinetype/
---
## NewLineType enum

Oluşturulan belgede kullanılacak yeni satır türü.

```cpp
enum class NewLineType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Windows | 0 | DOS ve Windows OS yeni satırı - \r\n |
| Unix | 1 | Unix ve Mac OS X yeni satırı - \n |
| Mac | 2 | Mac (OS 9) yeni satırı - \r |

## Açıklamalar

Örnek
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

## Diğerlerine Bakın

* İsim Uzayı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)