---
title: get_RefreshThumbnail()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션 썸네일을 새로 고칠지 여부를 지정합니다. 읽기 bool. 기본값은 true입니다.
type: docs
weight: 53
url: /ko/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() 메서드


프레젠테이션 썸네일을 새로 고칠지 여부를 지정합니다. 읽기 **bool**. 기본값은 **true**입니다.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## 비고


옵션 값이 **true**인 경우, 새 썸네일이 생성됩니다.

옵션 값이 **false**인 경우, 현재 썸네일이 그대로 저장됩니다.

예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## 참고

* 클래스 [PptxOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)