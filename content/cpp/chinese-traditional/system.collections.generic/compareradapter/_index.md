---
title: ComparerAdapter
second_title: Aspose.Slides for C++ API 參考文件
description: 在 STL 環境中使用 IComparer 的適配器。若已設定 IComparer，則使用它；否則，若可用則使用 operator <，若不可用則返回 false。
type: docs
weight: 638
url: /zh-hant/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

在 STL 環境中使用 [IComparer](../icomparer/) 的適配器。若已設定，使用 [IComparer](../icomparer/)；否則，使用 operator <（如果可用）或返回 false（如果不可用）。

```cpp
template<class T>class ComparerAdapter
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 被比較的類型。 |

## 方法

| 方法 | 描述 |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | 在沒有可用比較器的情況下構造適配器。 |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | 構造適配器。 |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) 函式，適用於具備 operator < 的類型。 |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) 函式，適用於不具備 operator < 的類型。 |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | 設定比較器物件。 |

## 另請參閱

* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)