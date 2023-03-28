---
title: ComparerType
second_title: Aspose.Slides for C++ API Reference
description: Compares elements using 'less' semantics.
type: docs
weight: 144
url: /cpp/system.collections.generic.details/comparertype/
---
## ComparerType struct


Compares elements using 'less' semantics.

```cpp
template<typename T>class ComparerType
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Compared elements type. |
## Methods

| Method | Description |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compares value types implementing [IComparable](../../system/icomparable/) interface. |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compares primitive value types and objects not implementing [IComparable](../../system/icomparable/) interface. |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compares floating point types. |

## See Also

* Namespace [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)
