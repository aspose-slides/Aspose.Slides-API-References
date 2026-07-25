---
title: Add()
second_title: Aspose.Slides の C++ API リファレンス
description: コレクションの末尾に新しいFallBackルールを追加します。
type: docs
weight: 14
url: /ja/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) メソッド

コレクションの末尾に新しいFallBackルールを追加します。

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | 追加するルールを指定します |

## 備考

```cpp
auto pres = MakeObject<Presentation>();
//FontsManager から空または事前に初期化されたルールコレクションを取得
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//コレクションに新しいルールを追加
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IFontFallBackRule](../../ifontfallbackrule/)
* クラス [IFontFallBackRulesCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)