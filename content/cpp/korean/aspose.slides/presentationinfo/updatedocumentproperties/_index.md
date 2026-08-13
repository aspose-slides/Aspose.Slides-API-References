---
title: UpdateDocumentProperties()
second_title: Aspose.Slides for C++ API 참조
description: 바인드된 프레젠테이션의 속성을 업데이트합니다.
type: docs
weight: 92
url: /ko/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) 메서드

바인드된 프레젠테이션의 속성을 업데이트합니다.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## 비고

이 샘플은 [PresentationInfo::UpdateDocumentProperties](./) 메서드를 호출하여 [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) 메서드 호출로 반환된 문서 속성을 업데이트하는 방법을 보여줍니다.
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDocumentProperties](../../idocumentproperties/)
* 클래스 [PresentationInfo](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)