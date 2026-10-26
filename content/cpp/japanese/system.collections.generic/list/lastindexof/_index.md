---
title: LastIndexOf()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定されたオブジェクトを検索し、リスト全体で最後に出現した位置のゼロベースインデックスを返します。
type: docs
weight: 469
url: /ja/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const メソッド

指定されたオブジェクトを検索し、リスト全体で最後に出現した位置のゼロベースインデックスを返します。

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | const T\& | リスト内で検索するオブジェクト |

### 戻り値

item が [List](../) 全体で最後に出現した位置のゼロベースインデックスを返します。見つからない場合は -1 を返します。

## List::LastIndexOf(const T\&, int32_t) const メソッド

指定されたオブジェクトを検索し、[List](../) の最初の要素から指定されたインデックスまでの範囲内で最後に出現した位置のゼロベースインデックスを返します。

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | const T\& | リスト内で検索するオブジェクト |
| index | **int32_t** | 後方検索の開始インデックス（ゼロベース）。 |

### 戻り値

item が [List](../) の最初の要素から index までの範囲内で最後に出現した位置のゼロベースインデックスを返します。見つからない場合は -1 を返します。

## List::LastIndexOf(const T\&, int32_t, int32_t) const メソッド

指定されたオブジェクトを検索し、[List](../) の指定された要素数を含み、指定されたインデックスで終了する範囲内で最後に出現した位置のゼロベースインデックスを返します。

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | const T\& | [List](../) 内で検索するオブジェクト |
| index | **int32_t** | 後方検索の開始インデックス（ゼロベース）。 |
| count | **int32_t** | 検索対象セクション内の要素数。 |

### 戻り値

item が [List](../) の count 個の要素を含み index で終了する範囲内で最後に出現した位置のゼロベースインデックスを返します。見つからない場合は -1 を返します。

## 参照

* クラス [List](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)