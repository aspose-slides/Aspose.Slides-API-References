---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 在集合末尾添加一个新的回退规则。
type: docs
weight: 14
url: /zh/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) 方法


在集合末尾添加一个新的回退规则。

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 指定用于添加的规则 |
## 备注



```cpp
auto pres = MakeObject<Presentation>();
//从 FontsManager 获取空的或预初始化的规则集合
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//向集合添加新规则
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRule](../../ifontfallbackrule/)
* Class [IFontFallBackRulesCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)