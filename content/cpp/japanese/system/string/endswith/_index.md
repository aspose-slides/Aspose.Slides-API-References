---
title: EndsWith()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 文字列が指定された部分文字列で終わるかどうかを確認します。
type: docs
weight: 482
url: /ja/system/string/endswith/
---
## String::EndsWith(const String\&) const メソッド

文字列が指定された部分文字列で終わるかどうかを確認します。

```cpp
bool System::String::EndsWith(const String &value) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../)\& | 検索文字列。 |

### 戻り値

文字列が指定された部分文字列で終わる場合は true、そうでない場合は false。

## String::EndsWith(const String\&, System::StringComparison) const メソッド

文字列が指定された部分文字列で終わるかどうかを確認します。

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../)\& | 検索文字列。 |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) モード、詳細は [System::StringComparison](../../stringcomparison/) を参照。 |

### 戻り値

文字列が指定された部分文字列で終わる場合は true、そうでない場合は false。

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const メソッド

文字列が指定された部分文字列で終わるかどうかを確認します。

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../)\& | 検索文字列。 |
| ignoreCase | **bool** | 比較が大文字と小文字を区別しないかどうかを指定します。 |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 文字列比較を行う際に使用するカルチャー。 |

### 戻り値

文字列が指定された部分文字列で終わる場合は true、そうでない場合は false。

## 参照

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)