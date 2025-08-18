---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 339
url: /system.collections.generic.details/
---



## Classes

| Class | Description |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable used by the IEnumerable.Cast() and IEnumerable.OfType() extension methods. |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable used by the IEnumerable.Select() extension method. |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator used by the IEnumerable.Cast() extension method. |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator used by the IEnumerable.OfType() extension method. |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator used by the IEnumerable.Select() extension method. |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## Structures

| Struct | Description |
| --- | --- |
| [ComparerType](./comparertype/) | Compares elements using 'less' semantics. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Compares elements using 'less' semantics. |
| [has_method_compareto](./has_method_compareto/) | Checks whether CompareTo method exists in specified type. If so, inherits std::true_type, otherwise inherits std::false_type. Can be used in std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Checks whether CompareTo(SharedPtr<T>) method exists in specified type. If so, inherits std::true_type, otherwise inherits std::false_type. Can be used in std::enable_if. |
| [IsEqualExist](./isequalexist/) | Checks if type provides operator ==. |
## Functions

| Function | Description |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Checks if index is out of container bounds, excluding container size. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Checks if index is out of container bounds, excluding container size. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Checks if index is out of container bounds, including container size. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Checks if index is out of container bounds, including container size. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Helper function to determine whether specific class has operator ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Helper function to determine whether specific class has operator ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Tries to get the first element of the collection. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Tries to get the first element of the collection, which satisfies to the predicate function. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Tries to get the last element of the collection. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Dummy typedef to check for operator == existance. |
