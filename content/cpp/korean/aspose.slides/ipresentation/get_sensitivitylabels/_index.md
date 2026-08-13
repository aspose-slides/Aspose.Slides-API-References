---
title: get_SensitivityLabels()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션 문서에 적용된 민감도 라벨 컬렉션을 반환합니다. 읽기 전용 ISensitivityLabelCollection.
type: docs
weight: 391
url: /ko/aspose.slides/ipresentation/get_sensitivitylabels/
---
## IPresentation::get_SensitivityLabels() 메서드


프레젠테이션 문서에 적용된 민감도 라벨 컬렉션을 반환합니다. 읽기 전용 [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
virtual System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::IPresentation::get_SensitivityLabels()=0
```

## 비고



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// 적용된 라벨을 출력합니다
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// 새 라벨을 추가합니다
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// 정책에서 민감도 라벨 ID를 가져옵니다
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// 정책에서 Azure AD 사이트 식별자를 가져옵니다
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* 클래스 [IPresentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)