---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API リファレンス
description: フォールバック機能による適切な置換のために、フォントのコレクションを管理するユーザーの FontFallBack ルールのコレクションを表します。IFontFallBackRulesCollection を記述します。
type: docs
weight: 40
url: /ja/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) メソッド

ユーザーの FontFallBack ルールのコレクションを表し、フォールバック機能による適切な置換のためにフォントのコレクションを管理します。[IFontFallBackRulesCollection](../../ifontfallbackrulescollection/) を記述します。

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## 備考

```cpp
auto pres = MakeObject<Presentation>();
// FontsManager から空または事前に初期化されたルールコレクションを取得
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// コレクションにルールを追加
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// or
// 新しいルールコレクションのインスタンスを初期化
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// コレクションにルールを追加
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// 既存のコレクションを FontsManager の新しいものに置き換え
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* クラス [IFontsManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)