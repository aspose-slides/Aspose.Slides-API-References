---
title: BinarySearch()
second_title: Aspose.Slides for C++ API リファレンス
description: ソートされたリスト内の項目を検索します。
type: docs
weight: 339
url: /ja/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const メソッド

ソートされたリスト内の項目を検索します。

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | const T\& | 検索対象の項目。 |

### 戻り値

[Index](../../../system/index/) ソートされたリスト内の項目のインデックス、または最も近いインデックスの補数。

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const メソッド

ソートされたリスト内の項目を検索します。

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | const T\& | 検索対象の項目。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) を使用します。 |

### 戻り値

[Index](../../../system/index/) ソートされたリスト内の項目のインデックス、または最も近いインデックスの補数。

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const メソッド

ソートされたリスト内の項目を検索します。

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) の開始位置。 |
| count | int | [Range](../../../system/range/) のサイズ。 |
| item | const T\& | 検索対象の項目。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) を使用します。 |

### 戻り値

[Index](../../../system/index/) ソートされたリスト内の項目のインデックス、または最も近いインデックスの補数。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [List](../)
* クラス [IComparer](../../icomparer/)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)