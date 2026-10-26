---
title: ComparerType
second_title: Aspose.Slides C++ API 参考
description: 使用 'less' 语义比较元素。
type: docs
weight: 144
url: /zh/system.collections.generic.details/comparertype/
---
## ComparerType 结构体

使用 ‘less’ 语义比较元素。

```cpp
template<typename T>class ComparerType
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 被比较元素的类型。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | 比较实现 [IComparable](../../system/icomparable/) 接口的值类型。 |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | 比较原始值类型以及未实现 [IComparable](../../system/icomparable/) 接口的对象。 |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | 比较浮点类型。 |

## 另请参见

* 命名空间 [System::Collections::Generic::Details](../)
* 库 [Aspose.Slides](../../)