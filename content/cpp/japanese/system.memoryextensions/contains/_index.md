---
title: Contains()
second_title: Aspose.Slides for C++ API リファレンス
description: 読み取り専用スパンに特定の値が含まれているかどうかを確認します。
type: docs
weight: 40
url: /ja/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) 関数


読み取り専用スパンに特定の値が含まれているかどうかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value | const T\& | 検索対象の値 |

### 戻り値

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) 関数


変更可能なスパンに特定の値が含まれているかどうかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のスパン |
| value | const T\& | 検索対象の値 |

### 戻り値

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 関数


文字スパンが、指定された比較ルールで別の文字スパンを含んでいるかどうかを確認します。

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 検索対象のスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 検索対象のスパン |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 実行する文字列比較の種類 |

### 戻り値

true if value is found in span, false otherwise

## 参照

* 列挙型 [StringComparison](../../system/stringcomparison/)
* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)