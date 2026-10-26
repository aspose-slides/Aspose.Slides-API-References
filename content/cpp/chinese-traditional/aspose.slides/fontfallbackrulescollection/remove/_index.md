---
title: Remove()
second_title: Aspose.Slides for C++ API 參考文件
description: 從集合中移除第一個出現的特定 FallBack 規則。
type: docs
weight: 53
url: /zh-hant/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) 方法

從集合中移除第一個出現的特定 FallBack 規則。

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 要從集合中移除的規則。 |
## 備註



```cpp
auto pres = MakeObject<Presentation>();
//從 FontsManager 獲取空的或已預先初始化的規則集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//向集合中加入多個規則
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//檢索集合中第一個規則的物件
auto firstRule = rulesList->idx_get(0);
//移除
rulesList->Remove(firstRule);
```


## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IFontFallBackRule](../../ifontfallbackrule/)
* 類別 [FontFallBackRulesCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)