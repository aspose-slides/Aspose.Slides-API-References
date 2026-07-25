---
title: FontFallBackRule()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 66
url: /ja/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) コンストラクタ


新しいインスタンスを作成します。

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | **uint32_t** | Unicode 範囲の開始インデックス |
| endIndex | **uint32_t** | Unicode 範囲の終了インデックス |
| fontNames | [System::String](../../../system/string/) | フォールバック用のフォント名または複数の名前（コンマで区切り） |
## 備考



```cpp
// FantFallBackRule の新しいインスタンスを 1 つのフォントで作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// FantFallBackRule の新しいインスタンスを複数のフォントで作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```


## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) コンストラクタ


新しいインスタンスを作成します。

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | **uint32_t** | Unicode 範囲の開始インデックス |
| endIndex | **uint32_t** | Unicode 範囲の終了インデックス |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | フォールバック用のフォント名または複数の名前（コンマで区切り） |
## 備考



```cpp
// FantFallBackRule の新しいインスタンスを 2 つのフォントで作成します
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// FantFallBackRule の新しいインスタンスを複数のフォントで作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [FontFallBackRule](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)