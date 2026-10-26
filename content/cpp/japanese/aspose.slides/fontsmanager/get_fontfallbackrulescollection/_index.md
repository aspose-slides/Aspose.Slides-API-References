---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API リファレンス
description: フォールバック機能による適切な置換のためにフォントのコレクションを管理する FontFallBack ルールのユーザーコレクションを表します。IFontFallBackRulesCollection を参照してください。
type: docs
weight: 27
url: /ja/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() メソッド


ユーザーの FontFallBack ルールのコレクションを表し、フォールバック機能による適切な置換のためにフォントのコレクションを管理します。[IFontFallBackRulesCollection](../../ifontfallbackrulescollection/) を参照してください。

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## 備考



```cpp
auto pres = MakeObject<Presentation>();
// FontsManager から空または事前初期化されたルールコレクションを取得
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// コレクションにルールを追加
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// または
// 新しいルールコレクションインスタンスの初期化
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// コレクションにルールを追加
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// FontsManager で既存のコレクションを新しいものに置き換える
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* クラス [FontsManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)