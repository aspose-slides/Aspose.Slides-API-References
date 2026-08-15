---
title: Remove()
second_title: Aspose.Slides C++ API 參考
description: 從集合中移除特定 FallBack 規則的第一個出現。
type: docs
weight: 27
url: /zh-hant/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) 方法

從集合中移除特定 FallBack 規則的第一個出現。

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 要從集合中移除的規則。 |
## 備註



```cpp
auto pres = MakeObject<Presentation>();
//從 FontsManager 獲取空的或預先初始化的規則集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//向集合中添加多個規則
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//檢索集合中第一個規則的對象
auto firstRule = rulesList->idx_get(0);
//刪除
rulesList->Remove(firstRule);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IFontFallBackRule](../../ifontfallbackrule/)
* 類別 [IFontFallBackRulesCollection](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)