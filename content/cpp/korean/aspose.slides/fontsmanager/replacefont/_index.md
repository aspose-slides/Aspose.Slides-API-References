---
title: ReplaceFont()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션에서 글꼴을 교체합니다
type: docs
weight: 118
url: /ko/aspose.slides/fontsmanager/replacefont/
---
## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontData\>, System::SharedPtr\<Aspose::Slides::IFontData\>) method

프레젠테이션에서 글꼴을 교체합니다

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontData> sourceFont, System::SharedPtr<Aspose::Slides::IFontData> destFont) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | 원본 글꼴 |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | 대상 글꼴 |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRule\>) method

[FontSubstRule](../../fontsubstrule/)에 제공된 정보를 사용하여 프레젠테이션의 글꼴을 교체합니다

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRule> substRule) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../../ifontsubstrule/)\> | 글꼴 대체 정보 |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRuleCollection\>) method

[FontSubstRule](../../fontsubstrule/) 컬렉션에 제공된 정보를 사용하여 프레젠테이션의 글꼴을 교체합니다

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRuleCollection> substRules) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | 글꼴 대체 규칙 컬렉션 |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontData](../../ifontdata/)
* 클래스 [FontsManager](../)
* 클래스 [IFontSubstRule](../../ifontsubstrule/)
* 클래스 [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)