---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides C++ API 參考
description: 代表使用者的 FontFallBack 規則集合，用於管理字型集合，以便透過回退功能執行正確的替換，寫入 IFontFallBackRulesCollection.
type: docs
weight: 40
url: /zh-hant/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) 方法


表示使用者的 FontFallBack 規則集合，用於管理字型集合，以便透過回退功能執行正確的替換寫入 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)。

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## 備註



```cpp
auto pres = MakeObject<Presentation>();
// 取得 FontsManager 中的空或預先初始化的規則集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// 將規則加入集合
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 或
// 初始化新的規則集合實例
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// 將規則加入集合
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 並在 FontsManager 中以新的集合取代現有集合
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* 類別 [FontsManager](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)