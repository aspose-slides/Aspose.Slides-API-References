---
title: Remove()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 특정 FallBack 규칙의 첫 번째 발생을 제거합니다.
type: docs
weight: 27
url: /ko/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) 메서드


컬렉션에서 특정 FallBack 규칙의 첫 번째 발생을 제거합니다.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 컬렉션에서 제거할 규칙입니다. |
## 비고



```cpp
auto pres = MakeObject<Presentation>();
//FontsManager에서 빈 또는 미리 초기화된 규칙 컬렉션 가져오기
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//컬렉션에 여러 규칙 추가
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//컬렉션에서 첫 번째 규칙 객체 가져오기
auto firstRule = rulesList->idx_get(0);
//제거
rulesList->Remove(firstRule);
```


## 또한 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontFallBackRule](../../ifontfallbackrule/)
* 클래스 [IFontFallBackRulesCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)