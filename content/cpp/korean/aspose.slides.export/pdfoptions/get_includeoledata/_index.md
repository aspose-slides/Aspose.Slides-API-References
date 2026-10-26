---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 True를 사용합니다. bool을 읽습니다.
type: docs
weight: 456
url: /ko/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() 메서드


True는 프레젠테이션의 모든 OLE 데이터를 결과 PDF의 포함된 파일로 변환합니다. 읽기 **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## 비고


기본값은 **false**입니다. 

예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 참고

* 클래스 [PdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)