---
title: Add()
second_title: C++용 Aspose.Slides API 참조
description: 지정된 FallBack 규칙을 컬렉션의 끝에 추가합니다.
type: docs
weight: 40
url: /ko/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) 메서드


지정된 FallBack 규칙을 컬렉션 끝에 추가합니다.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 추가할 규칙 지정 |
## 비고



```cpp
auto pres = MakeObject<Presentation>();
//FontsManager에서 비어 있거나 미리 초기화된 규칙 컬렉션을 가져오기
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//새 규칙을 컬렉션에 추가하기
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontFallBackRule](../../ifontfallbackrule/)
* 클래스 [FontFallBackRulesCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)