---
title: Count()
second_title: Aspose.Slides for C++ API リファレンス
description: 読み取り専用スパン内の値の出現回数をカウントします。
type: docs
weight: 118
url: /ja/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) 関数


読み取り専用スパン内のvalueの出現回数を数えます。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | span内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のspan |
| value | const T\& | カウントするvalue |

### 戻り値

valueがspanに現れる回数

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数


別の読み取り専用スパン内のspanの出現回数を数えます。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | spans内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のspan |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 出現回数を数えるspan |

### 戻り値

valueがspanに現れる回数

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) 関数


Span<T>内の単一のvalueの出現回数を数えます。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | span内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のspan |
| value | const T\& | 出現回数を数えるvalue |

### 戻り値

span内のvalueの出現回数

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数


Span<T>内のReadOnlySpan<T>の出現回数を数えます。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | spans内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象のspan |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 出現回数を数えるvalueを含むspan |

### 戻り値

valueがspanに現れる回数

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)