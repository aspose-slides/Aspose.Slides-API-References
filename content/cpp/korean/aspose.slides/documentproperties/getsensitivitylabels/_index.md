---
title: GetSensitivityLabels()
second_title: Aspose.Slides for C++ API 참조
description: 맞춤 문서 속성(Microsoft Information Protection SDK 메타데이터)에서 민감도 레이블 배열을 가져옵니다.
type: docs
weight: 859
url: /ko/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() 메서드

맞춤 문서 속성( Microsoft Information Protection SDK 메타데이터 )에서 민감도 레이블 배열을 가져옵니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## 비고

다음 코드는 맞춤 문서 속성에서 민감도 레이블 정보를 최신 SensitivityLabels 컬렉션으로 이동하는 방법을 보여줍니다:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// 맞춤 문서 속성에서 민감도 레이블을 가져옵니다
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // 컬렉션에 레이블을 추가합니다
    // 여기에서 레이블 정보의 유효성을 검사할 수 있습니다(레이블이 사용 가능한지 등)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [DocumentProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)