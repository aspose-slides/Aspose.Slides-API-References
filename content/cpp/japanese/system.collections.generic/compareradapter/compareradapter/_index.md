---
title: ComparerAdapter()
second_title: Aspose.Slides for C++ API リファレンス
description: 比較子が利用できない状態でアダプタを構築します。
type: docs
weight: 1
url: /ja/system.collections.generic/compareradapter/compareradapter/
---
## ComparerAdapter::ComparerAdapter() コンストラクタ


比較子が利用できない状態でアダプタを構築します。

```cpp
System::Collections::Generic::ComparerAdapter<T>::ComparerAdapter()
```

## ComparerAdapter::ComparerAdapter(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) コンストラクタ


アダプタを構築します。

```cpp
System::Collections::Generic::ComparerAdapter<T>::ComparerAdapter(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | 使用する比較子オブジェクト。 |

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IComparer](../../icomparer/)
* 構造体 [ComparerAdapter](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)