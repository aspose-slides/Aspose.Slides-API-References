---
title: idx_get()
second_title: Aspose.Slides C++ API 参考
description: 获取指定索引处的规则。只读 IFontFallBackRule.
type: docs
weight: 66
url: /zh/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) 方法


获取指定索引处的规则。只读 [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## 备注



```cpp
auto pres = MakeObject<Presentation>();
//从 FontsManager 获取空的或预初始化的规则集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//向集合添加若干规则
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//检索集合中第一个规则的对象
auto firstRule = rulesList->idx_get(0);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IFontFallBackRule](../../ifontfallbackrule/)
* 类 [FontFallBackRulesCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)