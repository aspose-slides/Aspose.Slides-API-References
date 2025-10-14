---
title: ListExt
second_title: Aspose.Slides for C++ API Reference
description: generic List class that implements IListWrapper interface
type: docs
weight: 443
url: /system.collections.generic/listext/
---
## ListExt class


generic [List](../list/) class that implements [IListWrapper](../../system.collections/ilistwrapper/) interface

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## Methods

| Method | Description |
| --- | --- |
| void [_add_range](../list/_add_range/)(std::initializer_list\<T\>) | C++ specific. |
| void [Add](../list/add/)(const T\&) override | Adds element to the end of list. |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | Adds elements to list; used when translating initializers. |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | Adds all elements from collection (or itself) to the end of current list. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | Gets read-only reference to this collection. |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | Gets iterator to the first element of collection. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | Gets iterator to the first element of the const-qualified collection. |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | Looks for item in a sorted list. |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Looks for item in a sorted list. |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Looks for item in a sorted list. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | Gets iterator to the first const-qualified element of collection. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | Gets iterator for a non-existent const-qualified element behind the end of the collection. |
| void [Clear](../list/clear/)() override | Deletes all elements. |
| **bool** [Contains](../list/contains/)(const T\&) const override | Checks if item is present in list. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Creates a list of elements converted to different type. |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Copies list elements into existing array elements. |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Copies all elements into existing array elements. |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Copies elements starting from the specified index into existing array elements. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | Gets a reverse iterator to the last const-qualified element of collection (first in reverse). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | [IListWrapper](../../system.collections/ilistwrapper/) interface implementation. |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) implementation helper for reference types. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) implementation helper for value types. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) implementation helper for other types. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | Gets a reverse iterator for a non-existent const-qualified element before the start of the collection. |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | Underlying data structure access function. |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | Underlying data structure access function. |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | Gets iterator for a non-existent element behind the end of the collection. |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | Gets iterator for a non-existent element behind the end of the const-qualified collection. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Checks if element adhering to specific predicate exists in list. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Looks for element adhering to specific predicate. |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Looks for elements adhering to specific predicate. |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Looks for element adhering to specific predicate. |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Looks for element adhering to specific predicate. |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Looks for element adhering to specific predicate. |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Looks for last element adhering to specific predicate. |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | Applies action to all elements in list. |
| int [get_Capacity](../list/get_capacity/)() const | Gets current list capacity. |
| int [get_Count](../list/get_count/)() const override | Gets number of elements in current list. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Checks whether the collection is of fixed size. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Checks if collection is read only. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Gets the object the collection is being synchronized through. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | Gets enumerator to iterate through list elements. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | Creates slice of list. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
|  [ICollection](../icollection/icollection/)() | Default constructor. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Copy constructor. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Move constructor. |
| T [idx_get](../list/idx_get/)(int) const override | Gets element at specific position. |
| void [idx_set](../list/idx_set/)(int, T) override | Sets element at specific position. |
| int [IndexOf](../list/indexof/)(const T\&) const override | Gets first index of specific item. |
| int [IndexOf](../list/indexof/)(const T\&, int) const | Looks for specific item in list. |
| void [Insert](../list/insert/)(int, const T\&) override | Inserts item at specified position. |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | Inserts data range at specific position. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | Searches for the specified object and returns the zero-based index of the last occurrence within the entire list. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the [List](../list/) that extends from the first element to the specified index. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the [List](../list/) that contains the specified number of elements and ends at the specified index. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applies an accumulator function over a sequence. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determines whether all elements of a sequence satisfy a condition. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Determines whether a sequence contains any elements. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determines whether any element of a sequence exists or satisfies a condition. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Casts the elements to the specified type. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatenates two sequences. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Determines if a sequence contains a specified value. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Returns the number of elements in the sequence (calculated via direct counting). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Returns the number of elements in the sequence that satisfy the specified condition. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Returns the element at a specified index in a sequence. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Returns the element at a specified index in a sequence. |
| T [LINQ_First](../ienumerable/linq_first/)() | Returns the first element of a sequence. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Returns the first element of a sequence that satisfy the specified condition. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Returns the first element of a sequence, or a default value if the sequence is empty. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Returns the first element of the sequence that satisfies a condition or a default value if no such element is found. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Groups the elements of a sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Returns the last element of a sequence. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Returns the last element of a sequence, or a default value if the sequence is empty. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invokes a transform function on each element of a generic sequence and returns the maximum resulting value. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invokes a transform function on each element of a generic sequence and returns the minimum resulting value. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filters the elements of the sequence based on the specified type. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorts the elements of a sequence in ascending order according to the key values selected by keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorts the elements of a sequence in descending order according to the key values selected by keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Inverts the order of the elements in a sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transforms elements of a sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transforms each element of a sequence into a new form by incorporating the element's index. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projects each element of a sequence and combines the resulting sequences into one sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Returns a specified number of contiguous elements from the start of a sequence. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Creates an array from a sequence. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Creates a List<T> from a sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filters a sequence based on the specified predicate. |
|  [List](../list/list/)() | Creates empty list. |
|  [List](../list/list/)(int) | Creates list with pre-defined capacity. |
|  [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | Copy constructor. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Move assignment operator. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Move assignment operator. |
| vector_t::reference [operator[]](../list/operator[]/)(int) | Accessor function. |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | Accessor function. |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | Gets a reverse iterator to the last element of collection (first in reverse). |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | Gets a reverse iterator to the last element of the const-qualified collection (first in reverse). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| **bool** [Remove](../list/remove/)(const T\&) override | Removes first instance of specific item from list. |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Removes all elements matching specific predicate. |
| void [RemoveAt](../list/removeat/)(int) override | Removes item at specified position. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [RemoveRange](../list/removerange/)(int, int) | Removes slice of list. |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | Gets a reverse iterator for a non-existent element before the start of the collection. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | Gets a reverse iterator for a non-existent element before the start of the const-qualified collection. |
| void [Reverse](../list/reverse/)() | Reverses elements order of the whole list. |
| void [Reverse](../list/reverse/)(int, int) | Reverses elements order of the list slice. |
| void [set_Capacity](../list/set_capacity/)(int) | Sets list capacity. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Sorts elements in the list. |
| void [Sort](../list/sort/)() | Sorts elements in the list using default comparator. |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Sorts elements in the list slice. |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Sorts elements in the list. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | Converst list to array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| void [TrimExcess](../list/trimexcess/)() | Makes list capacity to fit its size. |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Determines whether every element in the collection matches the conditions defined by the specified predicate. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |
## See Also

* Class [List](../list/)
* Class [IListWrapper](../../system.collections/ilistwrapper/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)