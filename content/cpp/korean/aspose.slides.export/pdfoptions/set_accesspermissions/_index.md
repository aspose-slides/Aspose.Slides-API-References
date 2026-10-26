---
title: set_AccessPermissions()
second_title: Aspose.Slides C++ API 레퍼런스
description: 문서를 사용자 액세스로 열 때 부여되어야 하는 접근 권한을 지정하는 플래그 집합을 포함합니다. PdfAccessPermissions를 참조하십시오.
type: docs
weight: 313
url: /ko/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) method


문서를 사용자 액세스로 열 때 부여되어야 하는 접근 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../../pdfaccesspermissions/)을(를) 참조하십시오.

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## 비고



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## 참조

* 열거형 [PdfAccessPermissions](../../pdfaccesspermissions/)
* 클래스 [PdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)