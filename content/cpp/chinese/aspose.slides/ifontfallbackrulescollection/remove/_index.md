---
title: Remove()
second_title: Aspose.Slides C++ API 参考
description: 从集合中移除特定 FallBack 规则的第一次出现。
type: docs
weight: 27
url: /zh/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) 方法

从集合中移除特定 FallBack 规则的第一次出现。

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 要从集合中移除的规则。 |
## 备注



```cpp
auto pres = MakeObject<Presentation>();
//从 FontsManager 获取空的或预初始化的规则集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//向集合添加多个规则
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//检索集合中第一个规则的对象
auto firstRule = rulesList->idx_get(0);
//移除
rulesList->Remove(firstRule);
```


## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IFontFallBackRule](../../ifontfallbackrule/)
* 类 [IFontFallBackRulesCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)