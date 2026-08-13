---
title: GetEffective()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 상속이 적용된 효과적인 3-D 서식 데이터를 가져옵니다.
type: docs
weight: 183
url: /ko/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() method

상속이 적용된 효과적인 3-D 서식 데이터를 가져옵니다.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```

### 반환 값

[IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).

## 비고

이 예제는 카메라, 라이트 리그 및 도형의 상단 베벨에 대한 효과적인 속성을 가져오는 방법을 보여줍니다.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto threeDEffectiveData = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_ThreeDFormat()->GetEffective();

Console::WriteLine(u"= Effective camera properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_Camera()->get_CameraType()));
Console::WriteLine(String(u"Field of view: ") + threeDEffectiveData->get_Camera()->get_FieldOfViewAngle());
Console::WriteLine(String(u"Zoom: ") + threeDEffectiveData->get_Camera()->get_Zoom());

Console::WriteLine(u"= Effective light rig properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_LightType()));
Console::WriteLine(String(u"Direction: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_Direction()));

Console::WriteLine(u"= Effective shape's top face relief properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_BevelTop()->get_BevelType()));
Console::WriteLine(String(u"Width: ") + threeDEffectiveData->get_BevelTop()->get_Width());
Console::WriteLine(String(u"Height: ") + threeDEffectiveData->get_BevelTop()->get_Height());
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Class [ThreeDFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)