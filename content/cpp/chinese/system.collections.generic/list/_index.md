---
title: List
second_title: Aspose.Slides for C++ API 参考
description: List 前向声明。
type: docs
weight: 430
url: /zh/system.collections.generic/list/
---
## List 类

[List](./) 前向声明。

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 元素类型。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++ 特定。 |
| void [Add](./add/)(const T\&) override | 将元素添加到列表的末尾。 |
| void [AddInitializer](./addinitializer/)(int, const T *) | 向列表添加元素；在翻译初始化器时使用。 |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | 将集合中的所有元素（或自身）添加到当前列表的末尾。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | 获取此集合的只读引用。 |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | 获取集合中第一个元素的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | 获取 const 限定集合中第一个元素的迭代器。 |
| int [BinarySearch](./binarysearch/)(const T\&) const | 在已排序的列表中查找项目。 |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | 在已排序的列表中查找项目。 |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | 在已排序的列表中查找项目。 |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | 获取集合中第一个 const 限定元素的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | 获取集合末尾后一个不存在的 const 限定元素的迭代器。 |
| void [Clear](./clear/)() override | 删除所有元素。 |
| **bool** [Contains](./contains/)(const T\&) const override | 检查列表中是否存在该项目。 |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | 创建一个将元素转换为不同类型的列表。 |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | 将列表元素复制到现有数组元素中。 |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | 将所有元素复制到现有数组元素中。 |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | 从指定索引开始，将元素复制到现有数组元素中。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 获取集合中最后一个 const 限定元素的反向迭代器（反向的第一个）。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 获取集合开始前一个不存在的 const 限定元素的反向迭代器。 |
| [vector_t](./vector_t/)\& [data](./data/)() | 底层数据结构访问函数。 |
| const [vector_t](./vector_t/)\& [data](./data/)() const | 底层数据结构访问函数。 |
| [iterator](../ienumerable/iterator/) [end](./end/)() | 获取集合末尾后一个不存在的元素的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | 获取 const 限定集合末尾后一个不存在的元素的迭代器。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | 检查列表中是否存在符合特定谓词的元素。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | 查找符合特定谓词的元素。 |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | 查找符合特定谓词的元素集合。 |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | 查找符合特定谓词的元素。 |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | 查找符合特定谓词的元素。 |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | 查找符合特定谓词的元素。 |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | 查找符合特定谓词的最后一个元素。 |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | 对列表中的所有元素执行操作。 |
| int [get_Capacity](./get_capacity/)() const | 获取当前列表容量。 |
| int [get_Count](./get_count/)() const override | 获取当前列表中的元素数量。 |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | 检查集合是否固定大小。 |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | 检查集合是否只读。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | 获取集合同步所使用的对象。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | 获取枚举器以遍历列表元素。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的散列。 |
| **ThisPtr** [GetRange](./getrange/)(int, int) | 创建列表的切片。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
|  [ICollection](../icollection/icollection/)() | 默认构造函数。 |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | 复制构造函数。 |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | 移动构造函数。 |
| T [idx_get](./idx_get/)(int) const override | 获取特定位置的元素。 |
| void [idx_set](./idx_set/)(int, T) override | 在特定位置设置元素。 |
| int [IndexOf](./indexof/)(const T\&) const override | 获取特定项目的第一个索引。 |
| int [IndexOf](./indexof/)(const T\&, int) const | 在列表中查找特定项目。 |
| void [Insert](./insert/)(int, const T\&) override | 在指定位置插入项目。 |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | 在特定位置插入数据范围。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | 在整个列表中搜索指定对象并返回其最后一次出现的从零开始的索引。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | 在[List](./)中从第一个元素到指定索引的范围内搜索指定对象，并返回其最后一次出现的从零开始的索引。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | 在[List](./)中包含指定数量元素且以指定索引结束的范围内搜索指定对象，并返回其最后一次出现的从零开始的索引。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 对序列应用累加函数。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | 确定序列的所有元素是否满足条件。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | 确定序列是否包含任何元素。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | 确定序列中是否存在任何元素或满足条件的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 将元素转换为指定类型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 连接两个序列。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | 确定序列是否包含指定值。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | 返回序列中元素的数量（通过直接计数计算）。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回满足指定条件的序列中元素的数量。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_First](../ienumerable/linq_first/)() | 返回序列的第一个元素。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回满足指定条件的序列的第一个元素。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | 返回序列的第一个元素；如果序列为空，则返回默认值。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 返回满足条件的序列的第一个元素；如果未找到，则返回默认值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 对序列的元素进行分组。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 对序列的元素进行分组。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | 返回序列的最后一个元素。 |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | 返回序列的最后一个元素；如果序列为空，则返回默认值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用转换函数，并返回最大结果值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用转换函数，并返回最小结果值。 |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | 根据指定类型过滤序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 按照 keySelector 选取的键值，对序列的元素进行升序排序。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 按照 keySelector 选取的键值，对序列的元素进行降序排序。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | 颠倒序列中元素的顺序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 转换序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 通过加入元素索引，将序列的每个元素转换为新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | 投影序列的每个元素并将产生的序列合并为一个序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | 从序列的开始返回指定数量的连续元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | 从序列创建数组。 |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | 从序列创建 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根据指定谓词过滤序列。 |
|  [List](./list/)() | 创建空列表。 |
|  [List](./list/)(int) | 创建具有预定义容量的列表。 |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | 复制构造函数。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | 移动赋值运算符。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | 移动赋值运算符。 |
| vector_t::reference [operator[]](./operator[]/)(int) | 访问函数。 |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | 访问函数。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 获取集合中最后一个元素的反向迭代器（反向的第一个）。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | 获取 const 限定集合中最后一个元素的反向迭代器（反向的第一个）。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [Remove](./remove/)(const T\&) override | 删除列表中第一个特定项目的实例。 |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | 删除所有匹配特定谓词的元素。 |
| void [RemoveAt](./removeat/)(int) override | 删除指定位置的项目。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [RemoveRange](./removerange/)(int, int) | 删除列表的切片。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 获取集合开始前一个不存在的元素的反向迭代器。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | 获取 const 限定集合开始前一个不存在的元素的反向迭代器。 |
| void [Reverse](./reverse/)() | 颠倒整个列表的元素顺序。 |
| void [Reverse](./reverse/)(int, int) | 颠倒列表切片的元素顺序。 |
| void [set_Capacity](./set_capacity/)(int) | 设置列表容量。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中切换指针为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | 对列表中的元素进行排序。 |
| void [Sort](./sort/)() | 使用默认比较器对列表中的元素进行排序。 |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | 对列表切片中的元素进行排序。 |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | 对列表中的元素进行排序。 |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | 将列表转换为数组。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| void [TrimExcess](./trimexcess/)() | 使列表容量恰好匹配其大小。 |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | 确定集合中的每个元素是否都满足指定谓词定义的条件。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 获取当前容器的 const begin 迭代器的实现。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 获取当前容器的 begin 迭代器的实现。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 获取当前容器的 const end 迭代器的实现。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 获取当前容器的 end 迭代器的实现。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~ICollection](../icollection/~icollection/)() | 析构函数。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [ValueType](./valuetype/) | 此类型。 |
| [BaseType](./basetype/) | 接口类型。 |
| [vector_t](./vector_t/) | 底层数据类型。 |
| [iterator](./iterator/) | 迭代器类型。 |
| [const_iterator](./const_iterator/) | 常量迭代器类型。 |
| [reverse_iterator](./reverse_iterator/) | 反向迭代器类型。 |
| [const_reverse_iterator](./const_reverse_iterator/) | 常量反向迭代器类型。 |
| [IEnumerablePtr](./ienumerableptr/) | 保存相同类型元素的容器。 |
| [IEnumeratorPtr](./ienumeratorptr/) | **枚举器** 类型。 |
## 备注

[List](./) - 用于翻译代码的 std::vector 包装器。需要为元素类型实现 operator ==。此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装在 [System::SmartPtr](../../system/smartptr/) 指针中，并使用该指针将其作为参数传递给函数。

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // 创建第一个列表。
  auto list1 = MakeObject<List<int>>();

  // 填充第一个列表。
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // 对第一个列表进行排序。
  // 第一个列表的项将为：{-5, 1, 3, 8}
  list1->Sort();

  // 删除索引为 2 的项。
  // 第一个列表的项将为：{-5, 1, 8}
  list1->RemoveAt(2);

  // 将项插入索引 1。
  // 第一个列表的项将为：{-5, 15, 1, 8}
  list1->Insert(1, 15);

  // 创建第二个列表。
  auto list2 = MakeObject<List<int>>();

  // 填充第二个列表。
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // 将第二个列表的元素追加到第一个列表。
  list1->AddRange(list2);

  // 打印第一个列表的项。
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
此代码示例产生以下输出:
- 5 15 1 8 10 20 30
*/
```

## 另见

* 类 [Object](../../system/object/)
* 类 [IList](../ilist/)
* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)