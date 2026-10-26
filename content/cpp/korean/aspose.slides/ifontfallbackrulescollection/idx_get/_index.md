---
title: idx_get()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인덱스에 있는 규칙을 가져옵니다. 읽기 전용 IFontFallBackRule.
type: docs
weight: 1
url: /ko/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) 메서드

지정된 인덱스에 있는 규칙을 가져옵니다. 읽기 전용 [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## 비고

```cpp
auto pres = MakeObject<Presentation>();
//FontsManager에서 비어 있거나 미리 초기화된 규칙 컬렉션 가져오기
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//컬렉션에 여러 규칙 추가
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//컬렉션에서 첫 번째 규칙 객체 가져오기
auto firstRule = rulesList->idx_get(0);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontFallBackRule](../../ifontfallbackrule/)
* 클래스 [IFontFallBackRulesCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)