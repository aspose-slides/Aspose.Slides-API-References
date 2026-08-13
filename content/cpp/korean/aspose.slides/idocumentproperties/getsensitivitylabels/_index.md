---
title: GetSensitivityLabels()
second_title: Aspose.Slides for C++ API 참조
description: 사용자 정의 문서 속성(Microsoft Information Protection SDK Metadata)에서 민감도 레이블 배열을 가져옵니다.
type: docs
weight: 872
url: /ko/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() 메서드

사용자 정의 문서 속성(Microsoft Information Protection SDK Metadata)에서 민감도 레이블 배열을 가져옵니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## 비고

다음 코드는 사용자 정의 문서 속성에서 민감도 레이블 정보를 최신 SensitivityLabels 컬렉션으로 이동하는 방법을 보여줍니다:

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// 사용자 지정 문서 속성에서 민감도 레이블 가져오기
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // 컬렉션에 레이블 추가
    // 여기서 레이블 정보의 유효성을 확인할 수 있습니다(레이블이 사용 가능한지 등)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISensitivityLabel](../../isensitivitylabel/)
* 클래스 [IDocumentProperties](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)