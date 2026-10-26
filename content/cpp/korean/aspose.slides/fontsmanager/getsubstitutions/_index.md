---
title: GetSubstitutions()
second_title: Aspose.Slides C++ API 레퍼런스
description: 프레젠테이션 렌더링 시 교체될 폰트에 대한 정보를 가져옵니다.
type: docs
weight: 66
url: /ko/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() 메서드

프레젠테이션 렌더링 시 교체될 폰트에 대한 정보를 가져옵니다.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```

### 반환값

모든 폰트 대체의 컬렉션 [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) 메서드

지정된 슬라이드 렌더링 중 교체될 폰트에 대한 정보를 가져옵니다.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 폰트 대체 정보를 검색할 슬라이드 인덱스 배열이며, 1부터 시작합니다. |

### 반환값

지정된 슬라이드에 대한 모든 폰트 대체 컬렉션([FontSubstitutionInfo](../../fontsubstitutioninfo/)).

## 비고

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* 클래스 [FontsManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)