---
title: ReplaceFont()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのフォントを置き換える
type: docs
weight: 118
url: /ja/aspose.slides/fontsmanager/replacefont/
---
## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontData\>, System::SharedPtr\<Aspose::Slides::IFontData\>) メソッド

プレゼンテーションのフォントを置き換えます

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontData> sourceFont, System::SharedPtr<Aspose::Slides::IFontData> destFont) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | ソースフォント |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | デスティネーションフォント |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRule\>) メソッド

[FontSubstRule](../../fontsubstrule/) で提供された情報を使用してプレゼンテーションのフォントを置き換えます

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRule> substRule) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../../ifontsubstrule/)\> | フォント置換情報 |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRuleCollection\>) メソッド

[FontSubstRule](../../fontsubstrule/) のコレクションに提供された情報を使用してプレゼンテーションのフォントを置き換えます

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRuleCollection> substRules) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | フォント置換ルールのコレクション |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IFontData](../../ifontdata/)
* クラス [FontsManager](../)
* クラス [IFontSubstRule](../../ifontsubstrule/)
* クラス [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)