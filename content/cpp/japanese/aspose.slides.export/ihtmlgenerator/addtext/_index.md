---
title: AddText()
second_title: Aspose.Slides for C++ API リファレンス
description: プレーンテキストを HTML ファイルに追加し、特殊文字を HTML エンティティに置き換えます。改行や空白文字は置き換えられません。
type: docs
weight: 92
url: /ja/aspose.slides.export/ihtmlgenerator/addtext/
---
## IHtmlGenerator::AddText(System::String) メソッド

プレーンテキストを HTML ファイルに追加し、特殊文字を HTML エンティティに置換します。改行と空白文字は置換されません。

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::String text)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 追加するテキスト。 |

## IHtmlGenerator::AddText(System::ArrayPtr\<char16_t\>) メソッド

プレーンテキストを HTML ファイルに追加し、特殊文字を HTML エンティティに置換します。改行と空白文字は置換されません。

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::ArrayPtr<char16_t> text)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 追加するテキスト。 |

## IHtmlGenerator::AddText(System::ArrayPtr\<char16_t\>, int32_t, int32_t) メソッド

プレーンテキストを HTML ファイルに追加し、特殊文字を HTML エンティティに置換します。改行と空白文字は置換されません。

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::ArrayPtr<char16_t> text, int32_t startIndex, int32_t length)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 追加するテキスト。 |
| startIndex | **int32_t** | 追加する部分の開始インデックス。 |
| length | **int32_t** | 追加する部分の長さ。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [IHtmlGenerator](../)
* 名前空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)