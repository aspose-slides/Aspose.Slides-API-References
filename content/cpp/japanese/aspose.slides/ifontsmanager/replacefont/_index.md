---
title: ReplaceFont()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのフォントを置き換える
type: docs
weight: 118
url: /ja/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) メソッド

プレゼンテーションのフォントを置き換える

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 元フォント |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 置換先フォント |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) メソッド

[IFontSubstRule](../../ifontsubstrule/)で提供された情報を使用してプレゼンテーションのフォントを置き換える

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | フォント置換情報 |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) メソッド

[IFontSubstRule](../../ifontsubstrule/)のコレクションで提供された情報を使用してプレゼンテーションのフォントを置き換える

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | フォント置換情報コレクション |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IFontData](../../ifontdata/)
* クラス [IFontsManager](../)
* クラス [IFontSubstRule](../../ifontsubstrule/)
* クラス [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)