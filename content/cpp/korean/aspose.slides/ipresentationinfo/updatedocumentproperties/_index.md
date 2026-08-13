---
title: UpdateDocumentProperties()
second_title: Aspose.Slides for C++ API 참조
description: 바인딩된 프레젠테이션의 속성을 업데이트합니다.
type: docs
weight: 92
url: /ko/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) 메서드


바인딩된 프레젠테이션의 속성을 업데이트합니다.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | 문서 속성 [IDocumentProperties](../../idocumentproperties/) |
## 비고



이 예제는 [IPresentationInfo::UpdateDocumentProperties](./) 메서드를 호출하여 [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) 메서드 호출로 반환된 문서 속성을 업데이트하는 방법을 보여줍니다.
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDocumentProperties](../../idocumentproperties/)
* Class [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)