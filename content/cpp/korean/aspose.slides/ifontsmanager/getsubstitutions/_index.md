---
title: GetSubstitutions()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션 렌더링 시 교체될 폰트에 대한 정보를 가져옵니다.
type: docs
weight: 66
url: /ko/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() 메서드


프레젠테이션 렌더링 시 교체될 폰트에 대한 정보를 가져옵니다.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### 반환 값

모든 폰트 교체의 컬렉션 [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## 비고




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) 메서드


지정된 슬라이드 렌더링 중에 교체될 폰트에 대한 정보를 가져옵니다.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 폰트 교체 정보를 검색할 슬라이드 인덱스 배열이며, 1부터 시작합니다. |

### 반환 값

지정된 슬라이드에 대한 모든 폰트 교체의 컬렉션 ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) 입니다.

## 비고




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* 클래스 [IFontsManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)