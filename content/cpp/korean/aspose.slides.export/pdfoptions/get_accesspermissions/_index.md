---
title: get_AccessPermissions()
second_title: Aspose.Slides for C++ API 참조
description: 문서가 사용자 액세스로 열릴 때 부여되어야 하는 액세스 권한을 지정하는 플래그 집합을 포함합니다. PdfAccessPermissions을(를) 참조하십시오.
type: docs
weight: 300
url: /ko/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() 메서드


문서가 사용자 액세스로 열릴 때 부여되어야 하는 액세스 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../../pdfaccesspermissions/)을(를) 참조하십시오.

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
```

## 비고



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## 관련 항목

* 열거형 [PdfAccessPermissions](../../pdfaccesspermissions/)
* 클래스 [PdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)