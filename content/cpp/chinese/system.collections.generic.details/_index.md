---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 352
url: /zh/system.collections.generic.details/
---
## 类

| 类 | 描述 |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | IEnumerable.Cast() 和 IEnumerable.OfType() 扩展方法使用的可枚举。 |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | IEnumerable.Select() 扩展方法使用的可枚举。 |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | IEnumerable.Cast() 扩展方法使用的枚举器。 |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | IEnumerable.OfType() 扩展方法使用的枚举器。 |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | IEnumerable.Select() 扩展方法使用的枚举器。 |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## 结构体

| 结构体 | 描述 |
| --- | --- |
| [ComparerType](./comparertype/) | 使用 'less' 语义比较元素。 |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | 使用 'less' 语义比较元素。 |
| [has_method_compareto](./has_method_compareto/) | 检查在指定类型中是否存在 CompareTo 方法。如果存在，则继承 std::true_type；否则继承 std::false_type。可用于 std::enable_if。 |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | 检查在指定类型中是否存在 CompareTo(SharedPtr<T>) 方法。如果存在，则继承 std::true_type；否则继承 std::false_type。可用于 std::enable_if。 |
| [IsEqualExist](./isequalexist/) | 检查类型是否提供 operator ==。 |
## 函数

| 函数 | 描述 |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | 检查索引是否超出容器范围（不包括容器大小）。 |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | 检查索引是否超出容器范围（不包括容器大小）。 |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | 检查索引是否超出容器范围（包括容器大小）。 |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | 检查索引是否超出容器范围（包括容器大小）。 |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | 帮助函数，用于确定特定类是否具有 operator ==。 |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | 帮助函数，用于确定特定类是否具有 operator ==。 |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | 尝试获取集合的第一个元素。 |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | 尝试获取集合中满足谓词函数的第一个元素。 |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | 尝试获取集合的最后一个元素。 |
## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | 用于检查 operator == 是否存在的虚拟类型别名。 |