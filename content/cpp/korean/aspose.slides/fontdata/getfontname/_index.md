---
title: GetFontName()
second_title: Aspose.Slides for C++ API 참조
description: 테마 참조를 실제 사용된 폰트로 교체하여 폰트 이름을 반환합니다.
type: docs
weight: 27
url: /ko/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) method

폰트 이름을 반환하며, 테마 참조를 실제 사용된 폰트로 교체합니다.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/)에서 테마된 폰트 이름을 가져와야 합니다. 올바른 값을 제공하는 것은 호출자에게 달려 있습니다. [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/)를 참조하십시오. |

### 반환값

폰트 이름.

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* 클래스 [FontData](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)