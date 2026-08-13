---
title: get_AccessPermissions()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 문서를 사용자 접근으로 열 때 부여되어야 하는 접근 권한을 지정하는 플래그 집합을 포함합니다. PdfAccessPermissions를 참조하십시오.
type: docs
weight: 261
url: /ko/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() 메서드


플래그 집합을 포함하고 있으며, 문서가 사용자 접근으로 열릴 때 부여되어야 하는 접근 권한을 지정합니다. 참조 [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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