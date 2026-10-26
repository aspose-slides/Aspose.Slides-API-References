---
title: FindIndex()
second_title: Aspose.Slides for C++ API リファレンス
description: 特定の述語に合致する要素を検索します。
type: docs
weight: 404
url: /ja/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) メソッド

特定の述語に一致する要素を検索します。

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 要素をチェックするための述語。 |

### 戻り値

[Index](../../../system/index/) 一致する要素のインデックス、または見つからない場合は -1。

## List::FindIndex(int, System::Predicate\<T\>) メソッド

特定の述語に一致する要素を検索します。

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) から検索を開始します。 |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 要素をチェックするための述語。 |

### 戻り値

[Index](../../../system/index/) 一致する要素のインデックス、または見つからない場合は -1。

## List::FindIndex(int, int, System::Predicate\<T\>) メソッド

特定の述語に一致する要素を検索します。

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) から検索を開始します。 |
| count | int | 検索対象の要素数。 |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 要素をチェックするための述語。 |

### 戻り値

[Index](../../../system/index/) 一致する要素のインデックス、または見つからない場合は -1。

## 参照

* typedef [Predicate](../../../system/predicate/)
* クラス [List](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)