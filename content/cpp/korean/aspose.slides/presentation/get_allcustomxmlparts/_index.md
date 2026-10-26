---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션의 모든 사용자 정의 데이터 파트를 반환합니다. 읽기 전용 ICustomXmlPart[].
type: docs
weight: 287
url: /ko/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() 메서드


프레젠테이션의 모든 사용자 정의 데이터 파트를 반환합니다. 읽기 전용 [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## 비고


다음 예제는 PowerPoint [Presentation](../)에서 모든 사용자 정의 XML 파트를 삭제하는 방법을 보여줍니다. 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ICustomXmlPart](../../icustomxmlpart/)
* 클래스 [Presentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)