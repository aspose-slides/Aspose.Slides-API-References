---
title: Equals()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列の等価比較です。StringComparison 列挙体が提供する複数のモードがサポートされています。
type: docs
weight: 391
url: /ja/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const メソッド


[String](../) 等価比較です。StringComparison 列挙体が提供するいくつかのモードがサポートされています。

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 現在のものと比較するために使用する。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) モード (詳細は [System::StringComparison](../../stringcomparison/) を参照)。 |

### 戻り値

選択された比較タイプで文字列が一致すれば true、そうでなければ false を返します。

## String::Equals(const String\&) const メソッド


[String](../) 等価比較です。[System::StringComparison::Ordinal](../../stringcomparison/) 比較モードを使用します。

```cpp
bool System::String::Equals(const String &str) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 現在のものと比較するために使用する。 |

### 戻り値

文字列が一致すれば true、そうでなければ false を返します。

## String::Equals(const String\&, const String\&) メソッド


2 つの文字列を Ordial 比較モードで等価比較します。

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| strA | const [String](../)\& | 比較対象の最初の文字列。 |
| strB | const [String](../)\& | 比較対象の2番目の文字列。 |

### 戻り値

文字列が一致すれば true、そうでなければ false を返します。

## String::Equals(const String\&, const String\&, System::StringComparison) メソッド


2 つの文字列を等価比較します。

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| strA | const [String](../)\& | 比較対象の最初の文字列。 |
| strB | const [String](../)\& | 比較対象の2番目の文字列。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) モード。 |

### 戻り値

文字列が一致すれば true、そうでなければ false を返します。

## 参照

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)