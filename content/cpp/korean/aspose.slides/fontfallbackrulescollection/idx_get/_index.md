---
title: idx_get()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스의 규칙을 가져옵니다. 읽기 전용 IFontFallBackRule.
type: docs
weight: 66
url: /ko/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) 메서드


지정된 인덱스의 규칙을 가져옵니다. 읽기 전용 [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## 비고



```cpp
auto pres = MakeObject<Presentation>();
//FontsManager에서 빈 또는 미리 초기화된 규칙 컬렉션 가져오기
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//컬렉션에 여러 규칙을 추가
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//컬렉션에서 첫 번째 규칙 객체를 가져오기
auto firstRule = rulesList->idx_get(0);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontFallBackRule](../../ifontfallbackrule/)
* 클래스 [FontFallBackRulesCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)