---
title: get_RefreshThumbnail()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션 썸네일이 새로 고쳐질지 여부를 지정합니다. 읽기 bool. 기본값은 true입니다.
type: docs
weight: 53
url: /ko/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() 메서드

프레젠테이션 썸네일이 새로 고쳐질지 지정합니다. 읽기 **bool**. 기본값은 **true**입니다.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## 비고

옵션 값이 **true**인 경우, 새로운 썸네일이 생성됩니다.

옵션 값이 **false**인 경우, 현재 썸네일이 그대로 저장됩니다.

예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## 참고

* 클래스 [IPptxOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)