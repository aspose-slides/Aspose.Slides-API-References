---
title: SortedList()
second_title: Aspose.Slides for C++ API リファレンス
description: 空のリストを作成します。
type: docs
weight: 1
url: /ja/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() コンストラクタ

空のリストを作成します。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) コンストラクタ

空のリストを作成します。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) を使用します。 |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) コンストラクタ

コピーコンストラクタ。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) からデータをコピーします。 |

## SortedList::SortedList(const map_t\&) コンストラクタ

コピーコンストラクタ。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | コピー元のマップ。 |

## SortedList::SortedList(int) コンストラクタ

空のリストを作成します。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | 確保する要素数。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [map_t](../map_t/)
* クラス [SortedList](../)
* クラス [IComparer](../../icomparer/)
* クラス [IDictionary](../../idictionary/)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)