---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API 参考
description: 表示用户的 FontFallBack 规则集合，用于管理字体集合，以便通过回退功能进行适当的替换 Write IFontFallBackRulesCollection.
type: docs
weight: 40
url: /zh/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) 方法

表示用户的 FontFallBack 规则集合，用于管理字体集合，以便通过回退功能进行适当的替换 Write [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## 备注



```cpp
auto pres = MakeObject<Presentation>();
// 从 FontsManager 获取空的或预初始化的规则集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// 将规则添加到集合中
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 或者
// 初始化规则集合的新实例
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// 将规则添加到集合中
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 并在 FontsManager 中用新集合替换现有集合
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* 类 [IFontsManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)