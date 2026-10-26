---
title: Dictionary()
second_title: Aspose.Slides for C++ API リファレンス
description: 空の辞書を作成します。
type: docs
weight: 1
url: /ja/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() コンストラクタ

空の辞書を作成します。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) コンストラクタ

マップからデータをコピーします。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | データをコピーするマップ。 |

## Dictionary::Dictionary(int) コンストラクタ

事前に割り当てられた辞書を作成するオーバーロードです。実際には割り当てを行いません。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | 割り当てる容量; 無視されます。 |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) コンストラクタ

コピーコンストラクタ。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) からデータをコピーします。 |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) コンストラクタ

コピーコンストラクタ。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | ソース辞書。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) オブジェクトを使用します。 |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) コンストラクタ

空の辞書を作成します。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) を使用します。 |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) コンストラクタ

空の辞書を作成します。

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | [Dictionary](../) 作成後の容量; 無視されます。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) を使用します。 |

## 参照

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Dictionary](../)
* Class [IDictionary](../../idictionary/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)