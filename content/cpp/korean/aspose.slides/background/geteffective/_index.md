---
title: GetEffective()
second_title: Aspose.Slides for C++ API 참조
description: 상속이 적용된 유효한 배경 데이터를 가져옵니다.
type: docs
weight: 118
url: /ko/aspose.slides/background/geteffective/
---
## Background::GetEffective() 메서드


상속이 적용된 유효한 배경 데이터를 가져옵니다.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### 반환값

다음 [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).

## 비고



이 예제는 유효한 배경 속성을 가져오는 방법을 보여줍니다. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* 클래스 [Background](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)