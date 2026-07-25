---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスのルールを取得します。読み取り専用 IFontFallBackRule。
type: docs
weight: 66
url: /ja/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) メソッド

指定されたインデックスのルールを取得します。 読み取り専用 [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## 備考

```cpp
auto pres = MakeObject<Presentation>();
//FontsManager から空または事前初期化されたルールコレクションの取得
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//コレクションに複数のルールを追加
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//コレクション内の最初のルールオブジェクトを取得
auto firstRule = rulesList->idx_get(0);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IFontFallBackRule](../../ifontfallbackrule/)
* クラス [FontFallBackRulesCollection](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)