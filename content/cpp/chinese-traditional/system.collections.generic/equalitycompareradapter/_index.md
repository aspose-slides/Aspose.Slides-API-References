---
title: EqualityComparerAdapter
second_title: Aspose.Slides C++ API 參考文件
description: "適配器使得可以使用 IEqualityComparer 搭配 STL 風格的集合與演算法。如已設定，使用 IEqualityComparer。若未設定，則使用 operator ==、Object::Equals 或 T::Equals，以可用者為準。"
type: docs
weight: 664
url: /zh-hant/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

Adapter 使得可以使用 [IEqualityComparer](../iequalitycomparer/) 搭配 STL 風格的集合與演算法。若已設定，使用 [IEqualityComparer](../iequalitycomparer/)。若未設定，則使用 operator ==、[Object::Equals](../../system/object/equals/) 或 T::Equals，以可用者為準。

```cpp
template<class T>class EqualityComparerAdapter
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| T | 被比較的類型。 |

## 方法

| 方法 | 描述 |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | 建立不使用任何比較器的適配器。 |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 建立使用給定比較器的適配器。 |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | 比較兩個物件。 |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 設定比較器。 |

## 另見

* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)