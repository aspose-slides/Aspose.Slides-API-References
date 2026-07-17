---
title: BehaviorPropertyCollection
second_title: Aspose.Slides for C++ API 参考
description: 表示效果行为的计时属性。
type: docs
weight: 66
url: /zh/aspose.slides.animation/behaviorpropertycollection/
---
## BehaviorPropertyCollection 类

表示效果行为的计时属性。

```cpp
class BehaviorPropertyCollection : public Aspose::Slides::Animation::IBehaviorPropertyCollection
```

## 方法

| Method | Description |
| --- | --- |
| void [Add](./add/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) override | 向集合添加新属性。 |
| void [Add](./add/)(const [System::String](../../system/string/)\&) override | 向集合添加新属性。 |
| [iterator](./iterator/) [begin](./begin/)() | 获取指向集合中第一个元素（如果有）的迭代器。 |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | 获取指向集合的 const 限定实例中第一个元素（如果有）的迭代器。 |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | 获取指向集合中第一个 const 限定元素（如果有）的迭代器。 |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | 获取指向集合中最后一个 const 限定元素之后的迭代器（如果有）。 |
| void [Clear](./clear/)() override | 从集合中移除所有属性。 |
| **bool** [Contains](./contains/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) const override | 确定 [ICollection](../../system.collections.generic/icollection/) 是否包含特定值。 |
| **bool** [Contains](./contains/)(const [System::String](../../system/string/)\&) const override | 确定 [ICollection](../../system.collections.generic/icollection/) 是否包含特定值。 |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\>, **int32_t**) override | 将 [ICollection](../../system.collections.generic/icollection/) 的元素复制到 [System::Array](../../system/array/)，从特定的 [System::Array](../../system/array/) 索引开始。 |
| virtual void [CopyTo](../../system.collections.generic/icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | 将所有集合元素复制到现有数组元素中。 |
| [iterator](./iterator/) [end](./end/)() | 获取指向集合中最后一个元素之后的迭代器（如果有）。 |
| [const_iterator](./const_iterator/) [end](./end/)() const | 获取指向集合的 const 限定实例中最后一个元素之后的迭代器（如果有）。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，两 NaN 不相等，仍将两个 NaN 视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，两 NaN 不相等，仍将两个 NaN 视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **int32_t** [get_Count](./get_count/)() const override | 返回集合中存储的属性数量。只读 **int32_t**。 |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | 检查集合是否具有固定大小。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | 获取指示 [ICollection](../../system.collections.generic/icollection/) 是否只读的值。只读 **bool**。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | 获取用于同步集合的对象。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\>\> [GetEnumerator](./getenumerator/)() override | 返回遍历集合的枚举器。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | 默认构造函数。 |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | 拷贝构造函数。 |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | 移动构造函数。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\> [idx_get](./idx_get/)(**int32_t**) const override | 返回指定索引处的属性。 |
| virtual T [idx_get](../../system.collections.generic/ilist/idx_get/)(int) const | 获取指定索引处的元素。 |
| void [idx_set](./idx_set/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>) override | 返回指定索引处的属性。 |
| virtual void [idx_set](../../system.collections.generic/ilist/idx_set/)(int, T) | 设置指定索引处的元素。 |
| **int32_t** [IndexOf](./indexof/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) const override | 确定 [IList](../../system.collections.generic/ilist/) 中特定项目的索引。 |
| **int32_t** [IndexOf](./indexof/)(const [System::String](../../system/string/)\&) const override | 通过属性值确定 [IList](../../system.collections.generic/ilist/) 中特定项目的索引。 |
| void [Insert](./insert/)(**int32_t**, const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) override | 在指定索引处向集合插入新属性。 |
| void [Insert](./insert/)(**int32_t**, [System::String](../../system/string/)) override | 在指定索引处向集合插入新属性（具有指定属性值）。 |
| virtual void [Insert](../../system.collections.generic/ilist/insert/)(int, const T\&) | 在指定位置插入元素，后续元素向后移动。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 对序列应用累加函数。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 确定序列的所有元素是否满足条件。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 确定序列是否包含任何元素。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 确定序列中是否存在任意满足条件的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 将元素转换为指定类型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 连接两个序列。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 确定序列是否包含指定值。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 返回序列中元素的数量（通过直接计数计算）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回满足指定条件的序列中元素的数量。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 返回序列的第一个元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回序列中满足指定条件的第一个元素。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 返回序列的第一个元素，如果序列为空则返回默认值。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 返回满足条件的序列第一个元素，如果未找到则返回默认值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 对序列的元素进行分组。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 对序列的元素进行分组。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 返回序列的最后一个元素。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 返回序列的最后一个元素，如果序列为空则返回默认值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用转换函数并返回最大结果值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用转换函数并返回最小结果值。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 根据指定类型过滤序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 根据 keySelector 选取的键值，以升序对序列的元素进行排序。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 根据 keySelector 选取的键值，以降序对序列的元素进行排序。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 反转序列中元素的顺序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 转换序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 通过加入元素索引，将序列的每个元素转换为新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 将序列的每个元素投影并将产生的序列合并为一个序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 返回序列起始处指定数量的连续元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 从序列创建数组。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 从序列创建 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根据指定的谓词过滤序列。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许为子类执行拷贝构造。 |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | 移动赋值运算符。 |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | 移动赋值运算符。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许为子类执行拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [Remove](./remove/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) override | 从集合中移除指定属性。 |
| **bool** [Remove](./remove/)(const [System::String](../../system/string/)\&) override | 从集合中移除指定属性。 |
| void [RemoveAt](./removeat/)(**int32_t**) override | 删除指定索引处的属性。 |
| virtual void [RemoveAt](../../system.collections.generic/ilist/removeat/)(int) | 删除指定索引处的元素。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数降低指定值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中切换指针为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 获取指向集合的 const 限定实例中第一个元素（如果有）的迭代器。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 获取指向集合中第一个元素（如果有）的迭代器。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 获取指向集合的 const 限定实例中最后一个元素之后的迭代器（如果有）。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | 获取指向集合中最后一个元素之后的迭代器（如果有）。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | 析构函数。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| Typedef | Description |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | 一种集合类型，其迭代器类型用作当前集合中的迭代器类型。 |
| [iterator](./iterator/) | 迭代器类型。 |
| [const_iterator](./const_iterator/) | 常量迭代器类型。 |
| [virtualized_iterator_element](./virtualized_iterator_element/) | 虚拟化的元素类型。 |
| [virtualized_iterator](./virtualized_iterator/) | 虚拟化类型。 |

## 另请参见

* 类 [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)
* 命名空间 [Aspose::Slides::Animation](../)
* 库 [Aspose.Slides](../../)