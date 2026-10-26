---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API 參考文件
description: 代表使用者的 FontFallBack 規則集合，用於管理字體集合，以便透過回退功能正確替換。閱讀 IFontFallBackRulesCollection.
type: docs
weight: 27
url: /zh-hant/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() 方法


代表使用者的 FontFallBack 規則集合，用於管理字體集合，以便透過回退功能正確替換。閱讀 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## 備註



```cpp
auto pres = MakeObject<Presentation>();
// 從 FontsManager 取得空的或預先初始化的規則集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// 將規則加入集合
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 或
// 初始化新的規則集合實例
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// 將規則加入集合
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
 // 並在 FontsManager 中以新集合取代現有集合
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* 類別 [FontsManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)