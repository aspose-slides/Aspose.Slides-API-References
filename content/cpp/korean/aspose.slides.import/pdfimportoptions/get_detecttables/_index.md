---
title: get_DetectTables()
second_title: Aspose.Slides for C++ API 레퍼런스
description: PDF 파일을 가져올 때 테이블을 감지할지 여부를 결정합니다.
type: docs
weight: 1
url: /ko/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const 메서드


pdf 파일을 가져올 때 테이블을 감지할지 여부를 결정합니다.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## 비고


예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## 참고

* 클래스 [PdfImportOptions](../)
* 네임스페이스 [Aspose::Slides::Import](../../)
* 라이브러리 [Aspose.Slides](../../../)