---
title: LINQ_Where()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 指定された述語に基づいてシーケンスをフィルタリングします。
type: docs
weight: 170
url: /ja/system.collections.generic/ienumerable/linq_where/
---
## IEnumerable::LINQ_Where(std::function\<bool(T)>) メソッド

指定された述語に基づいてシーケンスをフィルタリングします。

```cpp
SharedPtr<IEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_Where(std::function<bool(T)> predicate)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 各要素が特定の条件を満たすかテストする関数です。 |

### 戻り値

フィルタリングされた要素を含む[IEnumerable](../)です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IEnumerable](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)