---
title: SortedSet()
second_title: Aspose.Slides for C++ API リファレンス
description: 空のセットを作成します。
type: docs
weight: 1
url: /ja/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() コンストラクタ

空のセットを作成します。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) コンストラクタ

指定された容量で空のセットを作成します。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) コンストラクタ

指定された等価比較子を使用する空のセットを作成します。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) オブジェクトを [SortedSet](../) に関連付けます。 |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) コンストラクタ

[SortedSet](../) を列挙可能な値に基づいて作成します。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [SortedSet](../)
* クラス [IComparer](../../icomparer/)
* クラス [IEnumerable](../../ienumerable/)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)