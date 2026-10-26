---
title: Sort()
second_title: Aspose.Slides for C++ API リファレンス
description: リストの要素をソートします。
type: docs
weight: 521
url: /ja/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) メソッド

リストの要素をソートします。

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | 使用する比較子。 |

## List::Sort() メソッド

デフォルトの比較子を使用してリストの要素をソートします。

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) メソッド

リストのスライスの要素をソートします。

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | スライス開始インデックス。 |
| count | int | スライスサイズ。 |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | 使用する比較子。 |

## List::Sort(Comparison\<T\>, bool) メソッド

リストの要素をソートします。

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) を使用します。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IComparer](../../icomparer/)
* クラス [List](../)
* クラス [Comparison](../../../system/comparison/)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)