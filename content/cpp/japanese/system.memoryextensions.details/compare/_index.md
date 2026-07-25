---
title: Compare()
second_title: Aspose.Slides for C++ API リファレンス
description: 2つのスマートポインタを比較します。
type: docs
weight: 1
url: /ja/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) 関数


2つのスマートポインタを比較します。

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 最初のスマートポインタの型 |
| U | 2番目のスマートポインタの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | 最初のスマートポインタ |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | 2番目のスマートポインタ |

### 戻り値

[Comparison](../../system/comparison/) 結果 (等しい場合は0、a < b の場合は-1、a > b の場合は1)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) 関数


2つの算術値を比較します。

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 算術型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | const T\& | 最初の値 |
| b | const T\& | 2番目の値 |

### 戻り値

[Comparison](../../system/comparison/) 結果 (等しい場合は0、a < b の場合は-1、a > b の場合は1)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) 関数


スマートポインタと値を比較します。

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | スマートポインタが指す型 |
| U | 値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | スマートポインタ |
| b | const U\& | 値 |

### 戻り値

[Comparison](../../system/comparison/) 結果 (等しい場合は0、a < b の場合は-1、a > b の場合は1)

## 参照

* 型定義 [SharedPtr](../../system/sharedptr/)
* 名前空間 [System::MemoryExtensions::Details](../)
* ライブラリ [Aspose.Slides](../../)