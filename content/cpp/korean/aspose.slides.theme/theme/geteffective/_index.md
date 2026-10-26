---
title: GetEffective()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 상속이 적용된 효과적인 테마 데이터를 가져옵니다.
type: docs
weight: 53
url: /ko/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() 메서드

상속이 적용된 효과적인 테마 데이터를 가져옵니다.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```

### 반환 값

하나의 [IThemeEffectiveData](../../ithemeeffectivedata/).
## 비고

이 예제는 효과적인 테마 속성을 가져오는 방법을 보여줍니다.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IThemeEffectiveData](../../ithemeeffectivedata/)
* 클래스 [Theme](../)
* 네임스페이스 [Aspose::Slides::Theme](../../)
* 라이브러리 [Aspose.Slides](../../../)