---
title: Array
second_title: Aspose.Slides for C++ API 参考
description: "表示数组数据结构的类。该类的对象应仅使用 System::MakeArray() 和 System::MakeObject() 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言错误。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 14
url: /zh/system/array/
---
## Array 类

表示数组数据结构的类。该类的对象只能使用 [System::MakeArray()](../makearray/) 和 [System::MakeObject()](../makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | 数组元素的类型 |

## Methods

| Method | Description |
| --- | --- |
| void [Add](./add/)(const T\&) override | 不支持，因为当前对象表示的数组为只读。 |
| [Array](./array/)() | 构造一个空数组。 |
| [Array](./array/)(int, const T\&) | 填充构造函数。 |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | 填充构造函数。 |
| [Array](./array/)(int, const T) | 填充构造函数。 |
| [Array](./array/)(**vector_t**\&&) | 移动构造函数。 |
| [Array](./array/)(const **vector_t**\&) | 拷贝构造函数。 |
| [Array](./array/)(const std::vector\<Q\>\&) | 构造一个 [Array](./) 对象，并将其填充为从 std::vector（其值类型与 **T** 相同但不同于 **UnderlyingType**）复制的值。 |
| [Array](./array/)(std::vector\<Q\>\&&) | 构造一个 [Array](./) 对象，并将其填充为从 std::vector（其值类型与 **T** 相同但不同于 **UnderlyingType**）移动的值。 |
| [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | 构造一个 [Array](./) 对象，并将其填充为来自指定初始化列表（其中元素为 **UnderlyingType** 类型）的值。 |
| [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | 构造一个 [Array](./) 对象，并将其填充为来自指定数组（其中元素为 **UnderlyingType** 类型）的值。 |
| [Array](./array/)(std::initializer_list\<**bool**\>, int) | 构造一个 [Array](./) 对象，并将其填充为来自指定初始化列表（其中元素为 bool 类型）的值。 |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | 将数组转换为只读集合。 |
| [iterator](./iterator/) [begin](./begin/)() | 返回指向容器第一个元素的迭代器。如果容器为空，返回的迭代器将等于 [end()](./end/)。 |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | 返回指向 const 限定容器第一个元素的迭代器。如果容器为空，返回的迭代器将等于 [end()](./end/)。 |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | 对已排序的数组执行二分查找。 |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | 未实现。 |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | 返回指向容器第一个 const 限定元素的迭代器。如果容器为空，返回的迭代器将等于 [cend()](./cend/)。 |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | 返回指向容器最后一个元素之后的迭代器。该元素用作占位符；访问它会导致未定义行为。 |
| void [Clear](./clear/)() override | 不支持，因为当前对象表示的数组为只读。 |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | 用默认值替换指定数组中从 **startIndex** 开始的 **count** 个值。 |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | 克隆数组。 |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 从 [System.Array](./) 中复制一段元素，起始于指定的源位置。 |
| **bool** [Contains](./contains/)(const T\&) const override | 判断指定项是否在数组中。 |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | 构造一个新的 [Array](./) 对象，并使用指定的转换委托将指定数组的元素转换为 **OutputType** 类型后填充。 |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | 构造一个新的 [Array](./) 对象，并使用指定的转换函数对象将指定数组的元素转换为 **OutputType** 类型后填充。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | 将指定数量的元素从源数组复制到目标数组。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | 将指定数量的元素从源数组视图复制到目标数组。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | 将指定数量的元素从源数组复制到目标数组视图。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | 将指定数量的元素从源数组视图复制到目标数组视图。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | 将指定数量的元素从栈上的源数组复制到目标数组。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | 将指定数量的元素从源数组复制到栈上的目标数组。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | 将指定数量的元素从栈上的源数组复制到栈上的目标数组。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 将指定数量的元素从源数组的指定索引复制到目标数组的指定位置。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 将指定数量的元素从源数组视图的指定索引复制到目标数组的指定位置。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | 将指定数量的元素从源数组的指定索引复制到目标数组视图的指定位置。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | 将指定数量的元素从源数组视图的指定索引复制到目标数组视图的指定位置。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 将指定数量的元素从栈上的源数组的指定索引复制到目标数组的指定位置。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | 将指定数量的元素从源数组的指定索引复制到栈上的目标数组的指定位置。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | 将指定数量的元素从栈上的源数组的指定索引复制到栈上的目标数组的指定位置。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | 将指定数量的元素从源数组视图的指定索引复制到栈上的目标数组的指定位置。 |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | 将当前数组的所有元素复制到指定的目标数组。元素将从由 arrayIndex 参数指定的索引开始插入到目标数组。 |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | 将当前数组的所有元素复制到指定的目标数组。元素将从由 dstIndex 参数指定的索引开始插入到目标数组。 |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | 将当前数组的所有元素复制到指定的目标数组视图。元素将从由 dstIndex 参数指定的索引开始插入到目标数组视图。 |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | 将指定数量的元素从当前数组的指定位置复制到指定的目标数组。元素将从由 dstIndex 参数指定的索引开始插入到目标数组。 |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | 将指定数量的元素从当前数组的指定位置复制到指定的目标数组视图。元素将从由 dstIndex 参数指定的索引开始插入到目标数组视图。 |
| int [Count](./count/)() const | 返回一个数字，表示数组所有维度中所有元素的总数。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 返回指向已反转容器第一个元素的反向迭代器。它对应于未反转容器的最后一个元素。如果容器为空，返回的迭代器等于 [crend()](./crend/)。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 返回指向已反转容器最后一个元素之后的反向迭代器。它对应于未反转容器的第一个元素之前的元素。该元素为占位符，访问它会导致未定义行为。 |
| **vector_t**\& [data](./data/)() | 返回对内部用于存储数组元素的数据结构的引用。 |
| const **vector_t**\& [data](./data/)() const | 返回对内部用于存储数组元素的数据结构的常量引用。 |
| vector_t::pointer [data_ptr](./data_ptr/)() | 返回指向存储数组元素的内存缓冲区起始位置的原始指针。 |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | 返回指向存储数组元素的内存缓冲区起始位置的常量原始指针。 |
| [iterator](./iterator/) [end](./end/)() | 返回指向容器最后一个元素之后的迭代器。该元素为占位符，访问它会导致未定义行为。 |
| [const_iterator](./const_iterator/) [end](./end/)() const | 返回指向 const 限定容器最后一个元素之后的迭代器。该元素为占位符，访问它会导致未定义行为。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使两个 NaN 也被视为相等（尽管 IEC 60559:1989 中 NaN 不等于任何值，包括自身）。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 同上，对 double 类型进行 C# 风格的 NaN 相等比较。 |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | 判断指定的 [Array](./) 对象是否包含满足指定谓词要求的元素。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 在指定数组中搜索满足指定谓词条件的第一个元素。 |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 检索所有满足指定谓词条件的元素。 |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 在指定数组中搜索满足指定谓词条件的第一个元素。 |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | 对指定数组的每个元素执行指定操作。 |
| int [get_Count](./get_count/)() const override | 返回数组的大小。 |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | 检查集合是否具有固定大小。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | 表示数组是否为只读。 |
| **int32_t** [get_Length](./get_length/)() const override | 返回一个 32 位整数，表示数组所有维度中所有元素的总数。 |
| **int64_t** [get_LongLength](./get_longlength/)() const | 返回一个 64 位整数，表示数组所有维度中所有元素的总数。 |
| **int32_t** [get_Rank](./get_rank/)() const | 未实现。 |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | 获取用于同步集合的对象。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | 返回指向 **Enumerator** 对象的指针，该对象提供 IEnumerator 接口以遍历当前对象表示的数组元素。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | 类似 C# [Object.GetHashCode()](../object/gethashcode/) 方法，启用自定义对象的散列。 |
| int [GetLength](./getlength/)(int) | 返回指定维度中元素的数量。 |
| **int64_t** [GetLongLength](./getlonglength/)(int) | 以 64 位整数返回指定维度中元素的数量。 |
| int [GetLowerBound](./getlowerbound/)(int) const | 返回指定维度的下界。 |
| size_t [GetSizeTLength](./getsizetlength/)() const | 返回一个 std::size_t 变量，表示数组所有维度中所有元素的总数。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 获取对象的实际类型。类似 C# [System.Object.GetType()](../object/gettype/) 调用。 |
| int [GetUpperBound](./getupperbound/)(int) | 返回指定维度的上界。 |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | 默认构造函数。 |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | 拷贝构造函数。 |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | 移动构造函数。 |
| T [idx_get](./idx_get/)(int) const override | 返回指定索引处的项。 |
| void [idx_set](./idx_set/)(int, T) override | 将指定值设置为数组中指定索引处的项。 |
| int [IndexOf](./indexof/)(const T\&) const override | 确定指定项在数组中第一次出现的索引。 |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | 确定指定项在数组中第一次出现的索引。 |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | 确定指定项在数组中从指定索引开始的第一次出现的索引。 |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | 确定在由起始索引和范围长度定义的项范围内，指定项第一次出现的索引。 |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | 用指定数组的值填充当前对象表示的数组。 |
| void [Initialize](./initialize/)() | 使用类型 **T** 的默认构造对象填充数组。 |
| void [Insert](./insert/)(int, const T\&) override | 不支持，因为当前对象表示的数组为只读。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。类似 C# 的 `is` 运算符。 |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | 确定在由起始索引和范围长度定义的项范围内，指定项最后一次出现的索引。 |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | 确定从指定索引开始，指定项在数组中最后一次出现的索引。 |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | 确定指定项在数组中最后一次出现的索引。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | 对序列执行累加函数。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 判断序列的所有元素是否满足条件。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 判断序列是否包含任何元素。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 判断序列中是否存在满足条件的任意元素。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 将元素转换为指定类型。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 将两个序列连接起来。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 判断序列是否包含指定值。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 返回序列中元素的数量（通过直接计数计算）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | 返回满足指定条件的序列元素数量。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 返回序列的第一个元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | 返回满足指定条件的序列的第一个元素。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 返回序列的第一个元素，如果序列为空则返回默认值。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 返回满足条件的序列的第一个元素，如果不存在则返回默认值。 |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | 对序列的元素进行分组。 |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | 对序列的元素进行分组。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 返回序列的最后一个元素。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 返回序列的最后一个元素，如果序列为空则返回默认值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用转换函数并返回最大结果值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用转换函数并返回最小结果值。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 根据指定类型过滤序列的元素。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | 按 keySelector 选取的键值对序列进行升序排序。 |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | 按 keySelector 选取的键值对序列进行降序排序。 |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 反转序列中元素的顺序。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | 转换序列的元素。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | 通过合并元素索引，将序列的每个元素转换为新形式。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 将序列的每个元素投影并将产生的序列合并为一个序列。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 从序列开头返回指定数量的连续元素。 |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 从序列创建数组。 |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 从序列创建 List<T>。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根据指定谓词过滤序列。 |
| void [Lock](../object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | 使用 [operator<()](../operator_less/) 比较元素，查找数组中最大的元素。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 类似 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法，启用自定义类型的克隆。 |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | 使用 [operator<()](../operator_less/) 比较元素，查找数组中最小的元素。 |
| [Object](../object/object/)() | 创建对象并初始化所有内部数据结构。 |
| [Object](../object/object/)([Object](../object/) const\&) | 拷贝构造函数。实际上不拷贝任何内容，仅初始化新对象并允许子类拷贝构造。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 赋值运算符。实际上不拷贝任何内容，仅初始化新对象并允许子类拷贝构造。 |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | 移动赋值运算符。 |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | 移动赋值运算符。 |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | 返回指定索引处的项。 |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | 返回指定索引处的项。 |
| void * [raw_data_ptr](./raw_data_ptr/)() override | 返回单维数组第一个元素的指针。对于多维数组结果未定义。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 返回指向已反转容器第一个元素的反向迭代器。如果容器为空，返回的迭代器等于 [rend()](./rend/)。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | 返回指向已反转容器第一个元素的反向迭代器。如果容器为空，返回的迭代器等于 [rend()](./rend/)。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | 对字符串和 nullptr 情形的 [Object::ReferenceEquals](../object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | 对字符串情形的 [Object::ReferenceEquals](../object/referenceequals/) 特化。 |
| **bool** [Remove](./remove/)(const T\&) override | 不支持，因为当前对象表示的数组为只读。 |
| void [RemoveAt](./removeat/)(int) override | 不支持，因为当前对象表示的数组为只读。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 返回指向已反转容器最后一个元素之后的反向迭代器。它对应于未反转容器的第一个元素之前的元素。该元素为占位符，访问它会导致未定义行为。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | 返回指向已反转容器最后一个元素之后的反向迭代器。它对应于未反转容器的第一个元素之前的元素。该元素为占位符，访问它会导致未定义行为。 |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | 将指定数组的大小更改为指定值或创建具有指定大小的新数组。 |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | 反转指定数组中的元素。 |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | 反转指定数组中指定范围的元素。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 使数组将存储的指针视为弱引用（如果适用）。 |
| void [SetValue](./setvalue/)(const T\&, int) | 设置指定索引处元素的值。 |
| int [SharedCount](../object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 增加共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | 使用默认比较器对指定数组的元素进行排序。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | 使用默认比较器对指定数组中指定范围的元素进行排序。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | 使用指定比较器对指定数组的元素进行排序。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | 未实现。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | 使用指定比较对指定数组的元素进行排序。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | 对包含键的数组和对应项的数组进行排序，依据键数组的值进行比较（使用 operator<）。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | 对包含键的数组和对应项的数组进行排序，依据键数组的值进行比较（使用默认比较器）。 |
| virtual [String](../string/) [ToString](../object/tostring/)() const | 类似 C# [Object.ToString()](../object/tostring/) 方法，启用将自定义对象转换为字符串。 |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 判断指定数组的所有元素是否满足指定谓词定义的条件。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 实现 C# `typeof([System.Object](../object/))` 构造。 |
| void [Unlock](../object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 获取当前容器的 const begin 迭代器实现。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 获取当前容器的 begin 迭代器实现。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 获取当前容器的 const end 迭代器实现。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 获取当前容器的 end 迭代器实现。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 增加弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 减少弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | 析构函数。 |
| virtual  [~Object](../object/~object/)() | 销毁对象并释放所有内部数据结构。 |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | 数组元素类型的别名。 |
| [UnderlyingType](./underlyingtype/) | 表示数组中每个元素的类型的别名。 |
| [EnumerablePtr](./enumerableptr/) | 指向包含 **T** 类型元素的 IEnumerable 对象的共享指针类型别名。 |
| [EnumeratorPtr](./enumeratorptr/) | 指向包含 **T** 类型元素的 IEnumerator 对象的共享指针类型别名。 |
| [iterator](./iterator/) | 迭代器类型。 |
| [const_iterator](./const_iterator/) | 常量迭代器类型。 |
| [reverse_iterator](./reverse_iterator/) | 反向迭代器类型。 |
| [const_reverse_iterator](./const_reverse_iterator/) | 常量反向迭代器类型。 |

## Remarks

```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // 创建并填充数组。
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // 打印数组项。
  Print(arrayPtr);

  // 按升序排序数组项。
  Array<int32_t>::Sort(arrayPtr);

  // 打印数组项。
  Print(arrayPtr);

  // 打印数组项的计数。
  std::cout << arrayPtr->get_Length() << std::endl;

  // 打印等于 4 的项的索引。
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // 调整数组大小。
  Array<int32_t>::Resize(arrayPtr, 3);

  // 打印数组项。
  Print(arrayPtr);

  return 0;
}
/*
此代码示例产生以下输出:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## See Also

* Class [ArrayBase](../arraybase/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)