---
title: ComparerType
second_title: Aspose.Slides C++ API 參考文件
description: 使用「less」語意比較元素。
type: docs
weight: 144
url: /zh-hant/system.collections.generic.details/comparertype/
---
## ComparerType 結構

比較元素使用「less」語意。

```cpp
template<typename T>class ComparerType
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 被比較的元素型別。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | 比較實作 [IComparable](../../system/icomparable/) 介面的值類型。 |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | 比較原始值類型以及未實作 [IComparable](../../system/icomparable/) 介面的物件。 |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | 比較浮點類型。 |

## 另請參閱

* 命名空間 [System::Collections::Generic::Details](../)
* 函式庫 [Aspose.Slides](../../)