---
title: AddText()
second_title: Aspose.Slides for C++ API リファレンス
description: HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。改行や空白は置き換えられません。
type: docs
weight: 92
url: /ja/aspose.slides.export/htmlgenerator/addtext/
---
## HtmlGenerator::AddText(System::String) メソッド

HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。改行文字や空白は置き換えられません。

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::String text) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 追加するテキスト。 |

## HtmlGenerator::AddText(System::ArrayPtr\<char16_t\>) メソッド

HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。改行文字や空白は置き換えられません。

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::ArrayPtr<char16_t> text) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 追加するテキスト。 |

## HtmlGenerator::AddText(System::ArrayPtr\<char16_t\>, int32_t, int32_t) メソッド

HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。改行文字や空白は置き換えられません。

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::ArrayPtr<char16_t> text, int32_t startIndex, int32_t length) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 追加するテキスト。 |
| startIndex | **int32_t** | 追加する部分の開始インデックス。 |
| length | **int32_t** | 追加する部分の長さ。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [HtmlGenerator](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)