---
title: EndsWith()
second_title: Aspose.Slides for C++ API リファレンス
description: ReadOnlySpan<T> が単一の値で終了するかどうかを判断します。
type: docs
weight: 131
url: /ja/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) 関数


ReadOnlySpan<T> が単一の値で終了するかどうかを判断します。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | チェックするスパン |
| value | const T\& | スパンの末尾でチェックする値 |

### 戻り値

span がその値で終了すれば true、そうでなければ false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数


ReadOnlySpan<T> が別の ReadOnlySpan<T> で終了するかどうかを判断します。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | チェックするスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 対象スパンの末尾でチェックするスパン |

### 戻り値

span がその値で終了すれば true、そうでなければ false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数


Span<T> が ReadOnlySpan<T> で終了するかどうかを判断します。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | チェックするスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 対象スパンの末尾でチェックするスパン |

### 戻り値

span がその値で終了すれば true、そうでなければ false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) 関数


ReadOnlySpan<T> が Span<T> で終了するかどうかを判断します。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | チェックするスパン |
| value | const [Span](../../system/span/)\<T\>\& | 対象スパンの末尾でチェックするスパン |

### 戻り値

span がその値で終了すれば true、そうでなければ false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) 関数


Span<T> が別の Span<T> で終了するかどうかを判断します。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | チェックするスパン |
| value | const [Span](../../system/span/)\<T\>\& | 対象スパンの末尾でチェックするスパン |

### 戻り値

span がその値で終了すれば true、そうでなければ false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 関数


ReadOnlySpan<char16_t> が StringComparison を使用して指定された値で終了するかどうかを判断します。

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | チェックするスパン |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | スパンの末尾でチェックする値 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 使用する文字列比較の種類 |

### 戻り値

span がその値で終了すれば true、そうでなければ false

## 参照

* Enum [StringComparison](../../system/stringcomparison/)
* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)