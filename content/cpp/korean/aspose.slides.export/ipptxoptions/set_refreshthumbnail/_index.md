---
title: set_RefreshThumbnail()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션 썸네일을 새로 고칠지 여부를 지정합니다. bool 형식으로 씁니다. 기본값은 true 입니다.
type: docs
weight: 66
url: /ko/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) 메서드


프레젠테이션 썸네일을 새로 고칠지 여부를 지정합니다. **bool** 형식으로 씁니다. 기본값은 **true** 입니다.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## 비고


**true**인 경우 새 썸네일이 생성됩니다.

**false**인 경우 현재 썸네일이 그대로 저장됩니다.

예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## 참조

* 클래스 [IPptxOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)