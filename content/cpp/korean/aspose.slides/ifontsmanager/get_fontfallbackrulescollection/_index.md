---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 폰백 기능을 통한 적절한 대체를 위해 폰트 컬렉션을 관리하는 사용자의 FontFallBack 규칙 컬렉션을 나타냅니다. IFontFallBackRulesCollection을 읽으세요.
type: docs
weight: 27
url: /ko/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() 메서드


사용자의 FontFallBack 규칙 컬렉션을 나타내며, 폰트 컬렉션을 관리하여 폴백 기능을 통한 적절한 대체를 수행합니다. 읽기 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## 비고



```cpp
auto pres = MakeObject<Presentation>();
// FontsManager에서 빈 또는 미리 초기화된 규칙 컬렉션을 가져오기
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// 컬렉션에 규칙 추가
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 또는
// 규칙 컬렉션의 새 인스턴스 초기화
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// 컬렉션에 규칙 추가
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// FontsManager에서 기존 컬렉션을 새 컬렉션으로 교체하기
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* 클래스 [IFontsManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)