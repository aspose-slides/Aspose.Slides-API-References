---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API 참조
description: FontFallBack 규칙의 사용자 컬렉션을 나타내며, 폰트 컬렉션을 관리하여 폴백 기능을 통한 적절한 대체를 수행합니다. Write IFontFallBackRulesCollection.
type: docs
weight: 40
url: /ko/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) 메서드


FontFallBack 규칙의 사용자 컬렉션을 나타내며, 폰트 컬렉션을 관리하여 폴백 기능을 통한 적절한 대체를 수행합니다. Write [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## 비고



```cpp
auto pres = MakeObject<Presentation>();
// FontsManager에서 빈 또는 사전 초기화된 규칙 컬렉션 가져오기
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// 컬렉션에 규칙 추가
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// or
// 규칙 컬렉션의 새 인스턴스 초기화
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// 컬렉션에 규칙 추가
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 기존 컬렉션을 새 컬렉션으로 FontsManager에서 교체
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* 클래스 [FontsManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)