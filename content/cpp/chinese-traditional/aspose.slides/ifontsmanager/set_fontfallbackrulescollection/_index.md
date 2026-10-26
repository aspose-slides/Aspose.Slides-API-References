---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API 參考
description: 表示使用者的 FontFallBack 規則集合，用於管理字體集合，以便透過回退功能正確替換字體。寫入 IFontFallBackRulesCollection.
type: docs
weight: 40
url: /zh-hant/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) 方法


表示使用者的 FontFallBack 規則集合，用於管理字體集合，以便透過回退功能正確替換字體。寫入 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## 備註



```cpp
auto pres = MakeObject<Presentation>();
// 從 FontsManager 取得空的或已預先初始化的規則集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// 將規則加入集合
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 或
// 初始化規則集合的新實例
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// 將規則加入集合
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 並在 FontsManager 中以新集合取代現有的集合
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* 類別 [IFontsManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)