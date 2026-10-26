---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 True를 반환합니다. 읽기 bool.
type: docs
weight: 456
url: /ko/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() 메서드


프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 True를 반환합니다. 읽기 **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
```

## 비고


기본값은 **false** 입니다. 

예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 참조

* 클래스 [IPdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)