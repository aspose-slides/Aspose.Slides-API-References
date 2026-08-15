---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides for C++ API 參考文件
description: 用於散列 IEqualityComparer 的適配器。若已設定比較器，則使用該比較器；否則，使用使用 DictionaryHashSelector 結構選擇的可用散列方法。
type: docs
weight: 677
url: /zh-hant/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

用於散列 [IEqualityComparer](../iequalitycomparer/) 的適配器。若已設定比較器，則使用該比較器；否則，使用使用 [DictionaryHashSelector](../dictionaryhashselector/) 結構選擇的可用散列方法。

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### Template parameters

| Parameter | Description |
| --- | --- |
| Hashed | 型別。 |
## Methods

| Method | Description |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | 建立未使用比較器的適配器。 |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 建立使用給定比較器的適配器。 |
| std::size_t [operator()](./operator_call/)(const T\&) const | 計算散列值。 |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 設定要使用的比較器。 |

## See Also

* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)