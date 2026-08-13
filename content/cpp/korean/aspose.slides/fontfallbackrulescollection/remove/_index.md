---
title: Remove()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 특정 FallBack 규칙의 첫 번째 발생을 제거합니다.
type: docs
weight: 53
url: /ko/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) 메서드

컬렉션에서 특정 FallBack 규칙의 첫 번째 발생을 제거합니다.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 컬렉션에서 제거할 규칙. |
## 비고

```cpp
auto pres = MakeObject<Presentation>();
//FontsManager에서 비어 있거나 사전 초기화된 규칙 컬렉션 가져오기
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//여러 규칙을 컬렉션에 추가
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//컬렉션에서 첫 번째 규칙 객체 가져오기
auto firstRule = rulesList->idx_get(0);
//제거
rulesList->Remove(firstRule);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRule](../../ifontfallbackrule/)
* Class [FontFallBackRulesCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)