---
title: ValueTuple
second_title: Aspose.Slides for C++ API 参考
description: 表示 ValueTuple 数据结构的类。
type: docs
weight: 1418
url: /zh/system/valuetuple/
---
## ValueTuple 类

表示 [ValueTuple](./) 数据结构的类。

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | 确定当前对象和指定对象是否相同。 |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<Index, tuple_t\>\& [Item](./item/)() | 获取 [ValueTuple](./) 对象组件的值的引用。 |
| const std::tuple_element_t\<Index, tuple_t\>\& [Item](./item/)() const | 获取 [ValueTuple](./) 对象组件的值。 |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 将对象解构为此值元组。 |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 返回一个引用，指向表示 [ValueTuple](./) 类类型信息的 [TypeInfo](../typeinfo/) 对象。 |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | 构造一个元组对象。 |

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)