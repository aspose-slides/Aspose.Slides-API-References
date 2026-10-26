---
title: HashSet()
second_title: Aspose.Slides の C++ API リファレンス
description: RTTI 情報。
type: docs
weight: 1
url: /ja/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() constructor

RTTI 情報。

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## 備考

空のセットを作成します。

## HashSet::HashSet(int) constructor

指定された容量で空のセットを作成します。

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) constructor

指定された等価比較子を使用する空のセットを作成します。

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) オブジェクトを hashset に関連付けます。 |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructor

列挙可能な値に基づいてハッシュセットを作成します。

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [HashSet](../)
* クラス [IEqualityComparer](../../iequalitycomparer/)
* クラス [IEnumerable](../../ienumerable/)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)