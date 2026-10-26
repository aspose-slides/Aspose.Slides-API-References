---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션의 모든 OLE 데이터를 결과 PDF의 임베드된 파일로 변환하려면 True를 사용합니다. bool을 씁니다.
type: docs
weight: 469
url: /ko/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) 메서드

True를 지정하면 프레젠테이션의 모든 OLE 데이터를 결과 PDF의 임베드된 파일로 변환합니다. **bool**을 씁니다.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## 비고

기본값은 **false**입니다.  

예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 참조

* 클래스 [PdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)