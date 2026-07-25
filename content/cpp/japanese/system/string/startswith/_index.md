---
title: StartsWith()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列が指定された部分文字列で始まるかどうかをチェックします。
type: docs
weight: 469
url: /ja/system/string/startswith/
---
## String::StartsWith(const String\&) const メソッド


文字列が指定された部分文字列で始まるかどうかをチェックします。

```cpp
bool System::String::StartsWith(const String &value) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../)\& | 検索文字列。 |

### 戻り値

文字列が指定された部分文字列で始まる場合は true、そうでない場合は false。

## String::StartsWith(const String\&, System::StringComparison) const メソッド


文字列が指定された部分文字列で始まるかどうかをチェックします。

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../)\& | 検索文字列。 |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) モード、詳細は [System::StringComparison](../../stringcomparison/) を参照してください。 |

### 戻り値

文字列が指定された部分文字列で始まる場合は true、そうでない場合は false。

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const メソッド


文字列が指定された部分文字列で始まるかどうかをチェックします。

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../)\& | 検索文字列。 |
| ignoreCase | **bool** | 比較が大文字と小文字を区別しないかどうかを指定します。 |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 文字列比較を行う際に使用するカルチャー。 |

### 戻り値

文字列が指定された部分文字列で始まる場合は true、そうでない場合は false。

## 参照

* 列挙型 [StringComparison](../../stringcomparison/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [String](../)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)