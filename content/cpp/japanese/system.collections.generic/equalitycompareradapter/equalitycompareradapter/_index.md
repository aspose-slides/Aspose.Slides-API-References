---
title: EqualityComparerAdapter()
second_title: Aspose.Slides for C++ API リファレンス
description: コンパレーターを使用しないアダプターを作成します。
type: docs
weight: 1
url: /ja/system.collections.generic/equalitycompareradapter/equalitycompareradapter/
---
## EqualityComparerAdapter::EqualityComparerAdapter() コンストラクタ

コンパレーターを使用しないアダプターを作成します。

```cpp
System::Collections::Generic::EqualityComparerAdapter<T>::EqualityComparerAdapter()
```

## EqualityComparerAdapter::EqualityComparerAdapter(const SharedPtr\<IEqualityComparer\<T\>\>\&) コンストラクタ

指定されたコンパレーターを使用してアダプターを作成します。

```cpp
System::Collections::Generic::EqualityComparerAdapter<T>::EqualityComparerAdapter(const SharedPtr<IEqualityComparer<T>> &comparator)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | 使用するコンパレーター。 |

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IEqualityComparer](../../iequalitycomparer/)
* 構造体 [EqualityComparerAdapter](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)