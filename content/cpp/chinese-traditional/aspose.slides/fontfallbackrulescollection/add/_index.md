---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的 FallBack 規則新增至集合的末端。
type: docs
weight: 40
url: /zh-hant/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) method


將指定的 FallBack 規則新增至集合的末端。

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 用於新增的指定規則 |
## 備註



```cpp
auto pres = MakeObject<Presentation>();
//從 FontsManager 取得空的或預先初始化的規則集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//將新規則新增至集合
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## 另見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IFontFallBackRule](../../ifontfallbackrule/)
* 類別 [FontFallBackRulesCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)