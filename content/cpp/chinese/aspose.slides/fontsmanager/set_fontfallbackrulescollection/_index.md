---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides C++ API 参考
description: 表示用户的 FontFallBack 规则集合，用于通过回退功能管理字体集合，以实现适当的替换。写 IFontFallBackRulesCollection。
type: docs
weight: 40
url: /zh/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) 方法


表示用户的 FontFallBack 规则集合，用于管理字体集合，以便通过回退功能进行适当的替换 写 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)。

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## 备注



```cpp
auto pres = MakeObject<Presentation>();
// 从 FontsManager 获取空的或预初始化的规则集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// 向集合添加规则
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 或者
// 初始化规则集合的新实例
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// 向集合添加规则
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 在 FontsManager 中用新的集合替换现有集合
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* 类 [FontsManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)