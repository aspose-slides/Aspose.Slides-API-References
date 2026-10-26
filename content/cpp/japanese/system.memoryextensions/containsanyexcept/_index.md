---
title: ContainsAnyExcept()
second_title: Aspose.Slides for C++ API リファレンス
description: 読み取り専用スパンに、指定された 3 つの値を除く要素が含まれているかを確認します。
type: docs
weight: 66
url: /ja/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 関数

読み取り専用スパンに、指定された 3 つの値を除く要素が含まれているかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value0 | const T\& | 除外する最初の値 |
| value1 | const T\& | 除外する 2 番目の値 |
| value2 | const T\& | 除外する 3 番目の値 |

### 戻り値

指定された値と異なる要素が見つかった場合は true、そうでない場合は false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) 関数

可変スパンに、指定された 3 つの値を除く要素が含まれているかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の可変スパン |
| value0 | const T\& | 除外する最初の値 |
| value1 | const T\& | 除外する 2 番目の値 |
| value2 | const T\& | 除外する 3 番目の値 |

### 戻り値

指定された値と異なる要素が見つかった場合は true、そうでない場合は false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 関数

読み取り専用スパンに、指定された 2 つの値を除く要素が含まれているかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value0 | const T\& | 除外する最初の値 |
| value1 | const T\& | 除外する 2 番目の値 |

### 戻り値

指定された値と異なる要素が見つかった場合は true、そうでない場合は false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) 関数

可変スパンに、指定された 2 つの値を除く要素が含まれているかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の可変スパン |
| value0 | const T\& | 除外する最初の値 |
| value1 | const T\& | 除外する 2 番目の値 |

### 戻り値

指定された値と異なる要素が見つかった場合は true、そうでない場合は false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) 関数

読み取り専用スパンに、指定された 1 つの値を除く要素が含まれているかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| value | const T\& | 除外する値 |

### 戻り値

指定された値と異なる要素が見つかった場合は true、そうでない場合は false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) 関数

可変スパンに、指定された 1 つの値を除く要素が含まれているかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の可変スパン |
| value | const T\& | 除外する値 |

### 戻り値

指定された値と異なる要素が見つかった場合は true、そうでない場合は false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

読み取り専用スパンに、別のスパンに含まれる値を除く要素が含まれているかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパンの要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 検索対象のスパン |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 除外する値のスパン |

### 戻り値

values に含まれない要素が見つかった場合は true、そうでない場合は false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 関数

可変スパンに、読み取り専用スパンに含まれる値を除く要素が含まれているかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパンの要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 検索対象の可変スパン |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 除外する読み取り専用スパン |

### 戻り値

values に含まれない要素が見つかった場合は true、そうでない場合は false

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)