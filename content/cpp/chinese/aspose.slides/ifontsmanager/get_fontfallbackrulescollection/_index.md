---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides C++ API 参考
description: 表示用户用于管理字体集合以通过回退功能进行正确替换的 FontFallBack 规则集合。阅读 IFontFallBackRulesCollection.
type: docs
weight: 27
url: /zh/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() 方法


表示用户用于管理字体集合以通过回退功能进行正确替换的 FontFallBack 规则集合。阅读 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## 备注



```cpp
auto pres = MakeObject<Presentation>();
// 从 FontsManager 获取空的或预初始化的规则集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// 向集合添加规则
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 或者
// 初始化新的规则集合实例
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// 向集合添加规则
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 并在 FontsManager 中用新集合替换现有集合
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* 类 [IFontsManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)