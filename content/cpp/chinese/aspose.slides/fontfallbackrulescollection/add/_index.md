---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的 FallBack 规则添加到集合的末尾。
type: docs
weight: 40
url: /zh/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) 方法

将指定的 FallBack 规则添加到集合的末尾。

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 要添加的指定规则 |
## 备注

```cpp
auto pres = MakeObject<Presentation>();
//从 FontsManager 获取空的或预初始化的规则集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//向集合添加新规则
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IFontFallBackRule](../../ifontfallbackrule/)
* 类 [FontFallBackRulesCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)