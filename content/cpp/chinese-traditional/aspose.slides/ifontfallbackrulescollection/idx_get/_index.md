---
title: idx_get()
second_title: Aspose.Slides for C++ API 參考
description: 取得指定索引處的規則。唯讀 IFontFallBackRule.
type: docs
weight: 1
url: /zh-hant/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) 方法

取得指定索引處的規則。唯讀 [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## 備註



```cpp
auto pres = MakeObject<Presentation>();
//從 FontsManager 取得空的或已預先初始化的規則集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//將多個規則加入集合
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//取得集合中第一個規則的物件
auto firstRule = rulesList->idx_get(0);
```

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IFontFallBackRule](../../ifontfallbackrule/)
* 類別 [IFontFallBackRulesCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)