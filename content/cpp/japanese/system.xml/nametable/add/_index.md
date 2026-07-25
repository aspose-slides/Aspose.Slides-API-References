---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列をアトム化し、NameTableに追加します。
type: docs
weight: 14
url: /ja/system.xml/nametable/add/
---
## NameTable::Add(const String\&) メソッド


指定された文字列をアトム化し、[NameTable](../)に追加します。

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | 追加する文字列です。 |

### 戻り値

[NameTable](../)に既に存在する場合は、アトム化された文字列または既存の文字列が返されます。

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) メソッド


指定された文字列をアトム化し、[NameTable](../)に追加します。

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 追加する文字列を含む文字配列です。 |
| start | **int32_t** | 配列内の文字列の最初の文字を示す0ベースのインデックスです。 |
| len | **int32_t** | 文字列の文字数です。 |

### 戻り値

[NameTable](../)に既に存在する場合は、アトム化された文字列または既存の文字列が返されます。**len** が0の場合、[String::Empty](../../../system/string/empty/) が返されます。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [NameTable](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)