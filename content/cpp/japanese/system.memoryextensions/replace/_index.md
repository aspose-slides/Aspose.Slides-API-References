---
title: Replace()
second_title: Aspose.Slides for C++ API リファレンス
description: Span内のすべての値の出現を新しい値に置き換えます。
type: docs
weight: 287
url: /ja/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T&) 関数


[Span](../../system/span/)内のすべての値の出現を新しい値に置き換えます。

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | インラインで変更するスパン |
| oldValue | const T\& | 検索して置換する値 |
| newValue | const T\& | oldValue を置き換える新しい値 |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T&) 関数


コピー中に指定された値を置き換えながら、ソースからデスティネーションへ要素をコピーします。

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | コピー元の[ReadOnlySpan](../../system/readonlyspan/) |
| destination | [Span](../../system/span/)\<T\>\& | コピー先の[Span](../../system/span/) |
| oldValue | const T\& | コピー中に検索して置換する値 |
| newValue | const T\& | oldValue を置き換える新しい値 |

## 関連項目

* クラス [Span](../../system/span/)
* クラス [ReadOnlySpan](../../system/readonlyspan/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)