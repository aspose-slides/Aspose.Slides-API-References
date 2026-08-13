---
title: set_DetectTables()
second_title: Aspose.Slides C++용 API 참조
description: pdf 파일을 가져올 때 테이블을 감지할지 여부를 판단합니다.
type: docs
weight: 14
url: /ko/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) 메서드


pdf 파일을 가져올 때 테이블을 감지할지 여부를 결정합니다.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
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
* Library [Aspose.Slides](../../../)