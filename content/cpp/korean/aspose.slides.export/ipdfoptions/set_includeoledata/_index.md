---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ API 레퍼런스
description: True를 지정하면 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환합니다. bool 형식으로 작성합니다.
type: docs
weight: 469
url: /ko/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) 메서드

True를 사용하면 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환합니다. **bool** 형식으로 씁니다.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
```

## 비고

기본값은 **false**. 

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