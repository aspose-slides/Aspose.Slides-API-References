---
title: set_AccessPermissions()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문서가 사용자 접근으로 열릴 때 부여되어야 하는 액세스 권한을 지정하는 플래그 집합을 포함합니다. PdfAccessPermissions를 참조하십시오.
type: docs
weight: 274
url: /ko/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) 메서드


문서가 사용자 접근으로 열릴 때 부여되어야 하는 액세스 권한을 지정하는 플래그 집합을 포함합니다. 참조 [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
```

## 비고



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## 참고

* 열거형 [PdfAccessPermissions](../../pdfaccesspermissions/)
* 클래스 [IPdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)