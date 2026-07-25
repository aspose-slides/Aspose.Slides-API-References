---
title: Sort()
second_title: Aspose.Slides for C++ API リファレンス
description: カスタム比較子を使用して Span をソートします。
type: docs
weight: 339
url: /ja/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) 関数


カスタム比較子を使用して [Span](../../system/span/) をソートします。

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer object |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to sort |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

## System::MemoryExtensions::Sort(Span\<T\>\&) 関数


デフォルトの比較を使用して [Span](../../system/span/) をソートします。

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | The type of elements in the span |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The span to sort |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) 関数


カスタム比較子を使用してキーと値のペアをソートします（キーと値が一緒にソートされます）

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |
| TComparer | The type of the comparer object |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort (maintaining correspondence with keys) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for key comparison |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) 関数


比較デリゲートを使用してキーと値のペアをソートします。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegate for key comparison |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) 関数


デフォルトの比較を使用してキーと値のペアをソートします。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort |

## 参照

* 型定義 [SharedPtr](../../system/sharedptr/)
* クラス [Span](../../system/span/)
* クラス [Comparison](../../system/comparison/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)