---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션 끝에 새로운 FallBack 규칙을 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) 메서드

새로운 FallBack 규칙을 컬렉션 끝에 추가합니다.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 추가할 규칙 지정 |
## 비고

```cpp
auto pres = MakeObject<Presentation>();
//FontsManager에서 비어 있거나 사전 초기화된 규칙 컬렉션 가져오기
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//새 규칙을 컬렉션에 추가하기
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## 관련 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontFallBackRule](../../ifontfallbackrule/)
* 클래스 [IFontFallBackRulesCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)