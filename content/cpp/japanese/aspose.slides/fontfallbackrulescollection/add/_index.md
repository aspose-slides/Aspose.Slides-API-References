---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された FallBack ルールをコレクションの末尾に追加します。
type: docs
weight: 40
url: /ja/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) メソッド

指定された FallBack ルールをコレクションの末尾に追加します。

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 追加するための指定された規則 |
## 備考



```cpp
auto pres = MakeObject<Presentation>();
//FontsManager から空または事前初期化されたルールコレクションを取得
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//コレクションに新しいルールを追加
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRule](../../ifontfallbackrule/)
* Class [FontFallBackRulesCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)