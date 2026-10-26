---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides C++ API 참조
description: 사용자가 폰트 대체 기능으로 적절한 교체를 위해 폰트 컬렉션을 관리하는 FontFallBack 규칙 모음을 나타냅니다. IFontFallBackRulesCollection을 읽으십시오.
type: docs
weight: 27
url: /ko/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() 메서드


사용자가 폰트 대체 기능으로 적절한 교체를 위해 폰트 컬렉션을 관리하는 FontFallOut 규칙 모음을 나타냅니다. 읽으십시오 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## 비고



```cpp
auto pres = MakeObject<Presentation>();
// FontsManager에서 비어 있거나 사전 초기화된 규칙 컬렉션 가져오기
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// 컬렉션에 규칙 추가
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// or
// 규칙 컬렉션 새 인스턴스 초기화
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// 컬렉션에 규칙 추가
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 기존 컬렉션을 새 컬렉션으로 FontsManager에서 교체
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* 클래스 [FontsManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)