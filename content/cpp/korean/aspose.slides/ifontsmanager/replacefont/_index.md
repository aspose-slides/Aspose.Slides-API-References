---
title: ReplaceFont()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션에서 글꼴 교체
type: docs
weight: 118
url: /ko/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) 메서드

프레젠테이션에서 글꼴 교체

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 원본 글꼴 |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 대상 글꼴 |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) 메서드

제공된 [IFontSubstRule](../../ifontsubstrule/) 정보를 사용하여 프레젠테이션에서 글꼴 교체

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | 글꼴 치환 정보 |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) 메서드

컬렉션의 [IFontSubstRule](../../ifontsubstrule/) 정보를 사용하여 프레젠테이션에서 글꼴 교체

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | 글꼴 치환 정보 컬렉션 |

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontData](../../ifontdata/)
* 클래스 [IFontsManager](../)
* 클래스 [IFontSubstRule](../../ifontsubstrule/)
* 클래스 [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)