---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API リファレンス
description: フォールバック機能による適切な置換を行うために、フォントのコレクションを管理するユーザーの FontFallBack ルールのコレクションを表します。IFontFallBackRulesCollection を書き込みます。
type: docs
weight: 40
url: /ja/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) メソッド

ユーザーの FontFallBack ルールのコレクションを表し、フォールバック機能によって適切に置換されるフォントのコレクションを管理します。[IFontFallBackRulesCollection](../../ifontfallbackrulescollection/) を書き込みます。

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## 備考



```cpp
auto pres = MakeObject<Presentation>();
// FontsManager から空または事前初期化されたルールコレクションを取得
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// コレクションにルールを追加
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// または
// ルールコレクションの新しいインスタンスを初期化
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// コレクションにルールを追加
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// FontsManager で既存のコレクションを新しいものに置き換え
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* クラス [FontsManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)