---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API リファレンス
description: フォールバック機能による適切な代替のためにフォントのコレクションを管理する FontFallBack ルールのユーザーコレクションを表します。IFontFallBackRulesCollection を参照してください。
type: docs
weight: 27
url: /ja/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() メソッド

ユーザーの FontFallBack ルールコレクションを表し、フォールバック機能による適切な代替のためにフォントのコレクションを管理します。[IFontFallBackRulesCollection](../../ifontfallbackrulescollection/) を参照してください。

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
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
// FontsManager の既存コレクションを新しいものに置き換え
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* クラス [IFontsManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)