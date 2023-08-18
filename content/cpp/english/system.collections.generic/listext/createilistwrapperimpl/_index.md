---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides for C++ API Reference
description: IListWrapper implementation helper for reference types.
type: docs
weight: 14
url: /system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() method


[IListWrapper](../../../system.collections/ilistwrapper/) implementation helper for reference types.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() method


[IListWrapper](../../../system.collections/ilistwrapper/) implementation helper for value types.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() method


[IListWrapper](../../../system.collections/ilistwrapper/) implementation helper for other types.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections/ilist/)
* Class [ListExt](../)
* Struct [IsSmartPtr](../../../system/issmartptr/)
* Struct [IsBoxable](../../../system/isboxable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)