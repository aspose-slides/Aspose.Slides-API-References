---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションから特定のフォールバックルールの最初の出現を削除します。
type: docs
weight: 27
url: /ja/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) メソッド


コレクションから特定のフォールバックルールの最初の出現を削除します。

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | コレクションから削除するルール。 |
## 備考



```cpp
auto pres = MakeObject<Presentation>();
//FontsManager から空または事前初期化されたルールコレクションを取得
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//コレクションに複数のルールを追加
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//コレクション内の最初のルールのオブジェクトを取得
auto firstRule = rulesList->idx_get(0);
//削除
rulesList->Remove(firstRule);
```


## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IFontFallBackRule](../../ifontfallbackrule/)
* クラス [IFontFallBackRulesCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)